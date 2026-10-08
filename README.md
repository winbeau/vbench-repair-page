# VBench Repair · Project Page

[Visit the interactive project page](https://winbeau.github.io/vbench-repair-page/)

**Aligning VBench Scores with Their Intended Targets: Toward Faithful Video Evaluation**

This repository hosts the paper website, Figure 2, LTX counterfactual demonstrations, measured VBench/Ours scores and the frozen paper tables. The research code is maintained separately at [winbeau/vbench-repair](https://github.com/winbeau/vbench-repair) (repository access required).

## Preview

```sh
python3 scripts/site/build.py
npx --yes http-server site -p 8766 -c-1
```

Use an HTTP server with byte-range support for video seeking. GitHub Actions validates and publishes the static site on pushes to `winbeau`. Score provenance and asset hashes are downloadable under `site/data/`. Demonstration scores are separate from paper population means.

Visual inspiration: [Pyramid Forcing](https://if-lab-pku.github.io/Pyramid-Forcing/). Inter and Source Serif 4 licenses are included in `site/assets/fonts/`.
