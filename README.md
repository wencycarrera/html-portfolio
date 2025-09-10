README - html-portfolio
-----------------------

Files included:
- index.html
- contact.html
- assets/profile.jpg

Validation:
- These pages are written using semantic HTML5, include a single <h1> per page, and set lang="en" on <html>.
- Expectation: both files should pass the W3C HTML Validator with no errors.
- If you copy/paste into https://validator.w3.org/ and receive warnings (for example about missing longdesc or low-contrast), these are acceptable for this assignment but note them here and provide a short justification in this file.

How to use:
1. Extract the zip into a folder named html-portfolio (preserves structure).
2. Open index.html with any browser to preview.
3. Replace assets/profile.svg with your real profile.jpg if you prefer. Keep the filename 'profile.jpg' or update the <img> src accordingly.

Git quick commands (run inside the html-portfolio folder):
  git init
  git add .
  git commit -m "Initial commit: HTML-only portfolio"
  # Create a new empty repository on GitHub named html-portfolio (do NOT add README on GitHub)
  git remote add origin https://github.com/<your-username>/html-portfolio.git
  git branch -M main
  git push -u origin main

Common push error:
- If you see 'fatal: unable to access ...' when pushing, it's usually because:
  * You used angle brackets in the remote URL (remove them).
  * Your Git client needs authentication. Use HTTPS credential prompt or set up an SSH key and use the SSH remote URL.
  * Network or proxy issue. Try again or use GitHub Desktop for GUI push.

Deliverables checklist:
1) Remote repository URL: (paste your GitHub repo URL here)
2) Screenshot of successful push: take a screenshot after 'git push' showing the success message or view commit history on GitHub
3) GitHub Pages URL: enable Pages in repo settings (optional) and paste URL here

Good luck — sundan ang instructions (follow the instructions). If you want, I can also:
- Create a GitHub repo for you (I can't push to your account), or
- Show exact terminal commands for SSH key setup on Windows.