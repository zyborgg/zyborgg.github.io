# Ziah Cunningham — Portfolio

Plain HTML and CSS, no build step. Hosted on GitHub Pages at https://zyborgg.github.io/

## Updating

- `resume.pdf`: exported from the tech resume doc. Re-export and replace it when the resume changes.
- `images/`: 1280×800 screenshots of each live project.
- LinkedIn: add a link next to GitHub in the contact section once you have the URL.

## Publish to GitHub Pages

1. On GitHub, create a new **public** repo named exactly `zyborgg.github.io`.
2. In this folder:

   ```
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin git@github.com:zyborgg/zyborgg.github.io.git
   git push -u origin main
   ```

3. In the repo on GitHub: Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute or two the site is live at https://zyborgg.github.io/
