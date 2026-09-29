# Three exposures, one color image

This is the complete source for the published static website. The page's HTML, CSS, and JavaScript are in `dist/index.html`; `dist/assets/` contains the image files used by the page.

## Run locally

From this directory, run:

```sh
python3 -m http.server 8000 --directory dist
```

Then open http://localhost:8000. You can also open `dist/index.html` directly in a browser.

No build step or external dependency is required. Edit `dist/index.html` to change the layout, text, styles, offset table, or gallery.

The original plate alignment program (`part_two.py`) and source data archive were user supplied and are not included in this website package.
