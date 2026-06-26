# Delta Voice — Website

Static site for Delta Voice, a Cairo-based call center.

## Structure

- `index.html` — **Careers / job-seeker** site (the main page at the root domain).
- `business/index.html` — **Client / business** site, served at `/business`.

Both pages share the same design system and inline assets.

## Deployment (Cloudflare Pages)

This repo is connected to Cloudflare Pages for automatic deployment.

- **Framework preset:** None
- **Build command:** *(leave empty)*
- **Build output directory:** `/`

Every push to the default branch triggers a new deploy. `business/index.html`
is served automatically at `/business`.
