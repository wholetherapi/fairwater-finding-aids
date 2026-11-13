# Fairwater Municipal Archive — finding aids

Source content for the public finding-aid catalogue at
`https://archive.fairwater.example`.

- `finding-aids/` — one Markdown file per digitised collection, with YAML front matter
- `catalog/digitisation_registry.json` — data the catalogue API serves under `/api/digitisation-sources`
- `site.json` — build configuration for the static generator

The generator itself lives in the archive's infrastructure repository; run
`python build.py` from that checkout to rebuild the public site.
