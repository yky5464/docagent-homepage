# DOCAgent homepage

The public homepage of DOCAgent, served by GitHub Pages from the root of `main`
(no build step; `.nojekyll`). The custom domain is set in the repository's
Pages settings, after the domain is verified in the account's Pages settings.

- `index.html` — the homepage (Korean).
- `privacy.html`, `terms.html` — placeholders. The DOCAgent desktop app links to
  these two addresses, so replace the text and keep the paths.

Nothing here may load a third-party script, font or tracker: the page sets no
cookies and sends a visitor's address nowhere but GitHub.

Preview locally:

```
python -m http.server 8080
```

then open http://localhost:8080
