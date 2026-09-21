# Panel Notes — how to publish this on GitHub Pages (free)

## 1. Create a GitHub account
Go to github.com and sign up (free) if you don't have an account.

## 2. Create a new repository
- Click **New repository**.
- Name it exactly: `your-username.github.io` (replace `your-username` with your actual GitHub username — this exact naming is what makes GitHub Pages work at the root domain).
- Set it to **Public**.
- Don't add a README from GitHub's side (you already have one).
- Click **Create repository**.

## 3. Upload these files
- On your new repo's page, click **Add file → Upload files**.
- Drag in all files and folders from this site: `index.html`, `blog.html`, `about.html`, `style.css`, `README.md`, and the whole `posts` folder.
- Scroll down, click **Commit changes**.

## 4. Turn on GitHub Pages
- Go to the repo's **Settings → Pages**.
- Under "Build and deployment," set Source to **Deploy from a branch**.
- Branch: `main`, folder: `/ (root)`. Save.
- Wait 1-2 minutes. Your site will be live at `https://your-username.github.io`.

## 5. Adding a new blog post
1. Copy `posts/interview-questions-mv-switchgear.html` as a template.
2. Rename it to match your new post (e.g. `posts/autocad-vs-etap.html`).
3. Edit the `<title>`, the `<h1>`, the meta tag/date, and the body content.
4. Add a new `<li class="post-item">` block to both `index.html` (latest posts) and `blog.html` (all posts), linking to your new file.
5. Upload the changed/new files to GitHub the same way (Add file → Upload files) — this updates the live site automatically within a minute or two.

## Optional: custom domain later
If you buy a domain later (~₹700/year from Namecheap), you can point it at this same GitHub Pages site for free — no need to rebuild anything. Ask if you want help with that step when you get there.
