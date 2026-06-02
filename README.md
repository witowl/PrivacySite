# Snorvia Privacy Policy Page

Static bilingual privacy policy page for:

https://zenvale.com/snorvia/privacy

## Deploy to GitHub Pages

1. Create a public GitHub repository for the site.
2. Copy everything inside `Distribution/PrivacySite/` to that repository root.
3. Commit and push:

```bash
git add CNAME snorvia/privacy
git commit -m "Add Snorvia privacy policy page"
git push origin main
```

4. Open the repository on GitHub.
5. Go to `Settings > Pages`.
6. Choose `Deploy from a branch`.
7. Select branch `main` and folder `/ (root)`.
8. Set the custom domain to `zenvale.com`.
9. Enable `Enforce HTTPS` after GitHub finishes issuing the certificate.

If `zenvale.com` is not already configured for GitHub Pages, add the DNS records
required by GitHub Pages for an apex custom domain.

