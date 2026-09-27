# Wilbert Anadia — Portfolio

A single-file static portfolio (`index.html`). No build step, no dependencies.

## Before you deploy — replace these placeholders

1. **LinkedIn button** — appears in both the Contact section and the footer (`href="#"`). Replace `#` with your actual profile URL, e.g. `https://linkedin.com/in/your-handle`.
2. **GitHub link** — in the footer, replace the GitHub `href="#"` with your profile or repo URL.
3. **Project case study link** — in the Projects section, replace `href="#"` on "Case study →" with a real link, or remove it if there's no separate write-up.
4. **Résumé download** — the hero button links to `./resume.pdf`. Export your résumé as a PDF, name it `resume.pdf`, and place it in this same folder.

## Deploy to Vercel

**Option A — Vercel CLI**
```bash
npm install -g vercel
cd portfolio
vercel
```
Follow the prompts (accept the defaults — it's a static site, no framework needed). Run `vercel --prod` to push to your production URL.

**Option B — GitHub + Vercel dashboard**
1. Push this folder to a new GitHub repository.
2. Go to vercel.com → **Add New Project** → import that repository.
3. Framework preset: **Other** (or "Static"). Leave build command empty and output directory as `./`.
4. Click **Deploy**.

**Option C — Drag and drop**
Go to vercel.com/new, and drag this folder directly onto the page.

## Custom domain
Once deployed, add your domain (or a free `.vercel.app` subdomain) from the project's **Settings → Domains** tab in the Vercel dashboard.
