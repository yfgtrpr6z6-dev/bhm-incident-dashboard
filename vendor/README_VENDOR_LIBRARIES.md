# Vendor Libraries

The dashboard display, filters, charts, date ranges, KPI cards, and data tables are contained in `index.html`.

The files in this folder support export functions only:

- `exceljs.min.js` — Excel export
- `jspdf.umd.min.js` — PDF export
- `pptxgen.bundle.js` — PowerPoint export
- `html-to-image.js` — image capture used by PDF/PowerPoint export

Use browser-ready builds from the approved enterprise package source. The exact package names and versions are listed in `vendor-library-manifest.json`.

`index-cdn-enabled.html` is included as a working reference copy that uses the original jsDelivr export-library paths. `index.html` is the internal-hosting version that points to local files in this folder.
