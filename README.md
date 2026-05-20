# ቋንቋ to Career — Static Site (Vercel + Formspree)

## Files
- **index.html** → Homepage
- **login.html** → Student registration + sign-in
- **admin.html** → Admin dashboard
- **vercel.json** → Minimal Vercel config
- **README.md** → This file

## URLs After Deploy
- `your-site.vercel.app/`              → Homepage
- `your-site.vercel.app/login.html`    → Register/Sign In
- `your-site.vercel.app/admin.html`    → Admin

(Uses `.html` extensions for max compatibility with any host.)

## Deploy to Vercel (Drag & Drop)
1. Go to vercel.com → New Project → "Deploy without a Git repo" / Import
2. OR drag the folder onto a deployment URL
3. OR use CLI: `cd english-course && vercel --prod`

## If You're Still Getting 404
Check that the files are at the ROOT of your deploy, not inside a subfolder.
Visit `your-site.vercel.app/index.html` directly — if that works but `/` doesn't, 
your homepage isn't being detected as the root.

## Admin Login
- URL: `your-site.vercel.app/admin.html`
- Username: `admin`
- Password: `aylabs2026`

## Formspree
- Form: https://formspree.io/f/meedqrog
- All submissions land in Formspree inbox + email
- View submissions: https://formspree.io/forms/meedqrog/submissions
