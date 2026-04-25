# Yair Guri — Portfolio

This repository contains a single-file personal portfolio (`index.html`) with embedded CSS and JS.

## Deploy (GitHub Pages via Actions)
A GitHub Actions workflow is included that deploys the repository to GitHub Pages whenever you push to `main`.

Steps to publish (recommended):

1. Initialize git and commit:

```bash
cd C:\Users\yyrgw\Desktop\portfolio
git init
git add .
git commit -m "Initial portfolio"
```

2a. Create a repo and push (GitHub CLI):

```bash
gh repo create yair-portfolio --public --source=. --remote=origin --push
```

2b. Or create a repo on GitHub.com manually and then:

```bash
git remote add origin https://github.com/<your-username>/<repo>.git
git branch -M main
git push -u origin main
```

3. Wait a minute — the `pages` workflow will run and publish the site at `https://<your-username>.github.io/<repo>/`.

## Privacy note
- `index.html` currently contains a `mailto:` link and a WhatsApp link (phone). These will be public once published. If you want, remove or obfuscate them before pushing; alternatively I can replace them with a serverless contact form.

## Remove test file
If you don't want `test-toggle.html` published, delete it before committing.
