# ysalant.github.io

Personal academic homepage for Yuval Salant, built with [Jekyll](https://jekyllrb.com/)
and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Publishing on GitHub Pages

Since this uses `remote_theme`, no build step or GitHub Actions workflow is needed.
Just push this repo to GitHub and, in the repo's **Settings → Pages**, set the source
to the `main` branch (root). GitHub Pages supports `jekyll-remote-theme` natively.

## Content to fill in

The scaffold uses placeholders in square brackets, e.g. `[YOUR SHORT BIO]`. Search
the repo for `[` to find them all, or use the checklist below. Drop files directly
into the paths listed and edit the placeholder text.

### Text/config (edit directly)

| Location | What to add |
|---|---|
| `_config.yml` → `author.bio` | One-line bio for the sidebar (title + institution) |
| `_config.yml` → `author.links` | Google Scholar URL and Kellogg faculty directory URL |
| `index.md` | Short homepage welcome paragraph |
| `_pages/about.md` | Full bio: education, appointments, research interests |
| `_pages/publications.md` | List of published papers (title, coauthors, journal, year, links) |
| `_pages/working-papers.md` | List of working papers (title, coauthors, status, links) |

### Files to upload

| Path | What it is |
|---|---|
| `assets/images/bio-photo.jpg` | Your headshot/profile photo |
| `assets/files/cv.pdf` | Your CV |
| `assets/files/*.pdf` | Any paper PDFs you want to link from Publications/Working Papers |

If you'd rather just send me the text (bio, publication list, links) and photo/CV
files, drop them in this folder or paste them in chat and I'll wire everything in
for you.
