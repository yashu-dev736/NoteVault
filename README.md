# NoteVault

# NOTE VAULT — Static Site

This is a small static notes app. You can host it easily with GitHub Pages, Netlify, or Vercel.

Quick steps to publish on GitHub Pages (recommended):

1. Create a GitHub repository (e.g. `note-vault`).
2. Add a remote and push the current branch (`main`) to GitHub:

```bash
git remote add origin https://github.com/<YOUR_USERNAME>/<REPO>.git
git branch -M main
git push -u origin main
```

3. The repository includes a GitHub Actions workflow that deploys the site to the `gh-pages` branch automatically on push to `main`.
4. After the action completes, your site will be available at: `https://<YOUR_USERNAME>.github.io/<REPO>/`.

Alternative hosts:
- Netlify: drag-and-drop the project folder or connect your GitHub repo.
- Vercel: run `vercel` in the folder or connect your GitHub repo.

Files added to support automatic deployment:
- `.github/workflows/deploy.yml` (GitHub Actions to deploy to GitHub Pages)

If you want, I can also create a `CNAME` for a custom domain or add an Import feature.

----
Created automatically by the development assistant.
