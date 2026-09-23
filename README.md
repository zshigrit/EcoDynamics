# Zheng Shi — academic website

Personal academic website for Zheng Shi, Research Scientist at the Institute for Environmental Genomics, University of Oklahoma.

**Live site:** https://zshigrit.github.io/EcoDynamics/

The site is written in [MyST Markdown](https://mystmd.org/) and published to GitHub Pages by [the deployment workflow](.github/workflows/deploy.yml) when changes are merged into `main`.

## Edit the site

- `myst.yml` sets the title and page navigation.
- `index.md` is the homepage.
- `research.md`, `publications.md`, `background.md`, and `contact.md` are the other pages.
- `custom.css` contains small visual adjustments.

To build locally, install MyST (`npm install -g mystmd`) and run `myst build --html`. The output is in `_build/html/`.
