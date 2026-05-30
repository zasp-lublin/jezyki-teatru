# Flipbook – Języki Teatru

An HTML flipbook hosted on GitHub Pages.

## Structure

```
/
├── index.html                                  ← flipbook viewer
├── pages/
│   ├── page-01.png … page-26.png              ← rendered PDF pages
└── Jezyki teatru. Niezbednik Mlodego Widza.pdf ← original PDF (for download)
```

## Deploy to GitHub Pages

1. Create a new GitHub repository (public).
2. Push this entire folder:
   ```bash
   git init
   git add .
   git commit -m "Initial flipbook"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your repo.
4. Set Source to **Deploy from a branch → main → / (root)**.
5. Save. Your flipbook will be live at:
   `https://YOUR_USERNAME.github.io/YOUR_REPO/`
