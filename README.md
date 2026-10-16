# TalentLens — AI-assisted recruitment platform (Demo Prototype)

Single-file web app (vanilla JS, no build step). Data is stored in the browser (`localStorage`); no backend, no login.

**Sections:** Dashboard · Jobs · Candidates · Matching · Insights · Hiring Pipeline (Kanban)
**Languages:** English, Русский, Oʻzbekcha
**AI:** rule-based "Demo Prototype AI" (match explanation, skill gaps, interview questions) — no external API.

## Run locally
Open `index.html` in a browser (or `python3 -m http.server`).

## Deploy (GitHub Pages)
Push to `main`; the workflow in `.github/workflows/pages.yml` publishes the site.
In the repo: **Settings → Pages → Source: GitHub Actions**. Live URL: `https://<user>.github.io/<repo>/`.

## 5-step demo
1. Jobs → Create New Job · 2. Candidates → Add Candidate · 3. Matching → Run AI Matching ·
4. Read the AI breakdown · 5. Pipeline → move the candidate between stages.

`Reset demo data` (sidebar) restores the seed data.
