# Yueming Gao — Personal Website

**Live site: https://yg674-dev.github.io/**

A single-page personal site: AI Product Manager · Trust & Safety · Data Science.
Built as static HTML/CSS/JS and served by GitHub Pages from `main`.

## Sections

| Anchor | Section |
| --- | --- |
| `#home` | Hero |
| `#about` | About |
| `#experience` | Experience |
| `#education` | Education |
| `#community` | Community |
| `#contact` | Contact |

## Structure

```
index.html        page markup, all six sections
css/style.css     styles
js/main.js        nav, scroll, mobile menu
assets/           images
```

## Running it locally

No build step. Either open `index.html` directly, or serve the folder so the
relative paths behave exactly as they do in production:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

GitHub Pages builds from the root of `main`. Push to `main` and the live site
updates on its own — there is no workflow to run.
