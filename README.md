# Ye Rin Park — Academic Portfolio

Personal academic website of Ye Rin Park, Ph.D. Candidate at KAIST.

Website: https://ye-rin-park.github.io

Built with [Astro](https://astro.build) on top of the [Astrofy](https://github.com/manuelernestog/astrofy) template (MIT License, see `LICENSE`).

## Local development

This project uses npm.

```bash
npm install
npm run dev      # start local dev server
npm run build    # production build to ./dist
npm run preview  # preview the production build locally
```

## Deployment

Pushing to `main` triggers the GitHub Actions workflow in `.github/workflows/deploy.yml`,
which builds the site with Astro and publishes it to GitHub Pages.

## Content to update

- No CV PDF is currently included. To add one, place it at `public/CV_YeRinPark.pdf` and link it
  from `src/pages/cv.astro`.
- Email, LinkedIn, and Google Scholar links were omitted because they were not available in the
  repository; add them to `src/components/SideBarFooter.astro` when available.

## Existing files preserved

The following conference poster PDFs existed in the repository before this rebuild and were moved
into `public/` so their public URLs stay exactly the same:

- `/2025-ECCO_Poster.pdf`
- `/ADPD-2025_CJRB-302.pdf`
- `/CJRB-302-SfN-Poster-final-2024.pdf`
- `/ISMB2026_poster_PYR.pdf`
