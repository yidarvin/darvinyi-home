# darvinyi.com

Personal portfolio site for Darvin Yi. Vanilla HTML/CSS — no framework, no build step.

## Run locally

```bash
npx serve .
```

Then open http://localhost:3000.

## Deploy to Vercel

```bash
npx vercel
```

Vercel auto-detects static sites with no config needed. To link to a custom domain, add `darvinyi.com` in the Vercel project settings under Domains.

## Structure

```
darvinyi/
├── index.html   # entire site — all CSS inlined, no external dependencies except Google Fonts
└── README.md
```
