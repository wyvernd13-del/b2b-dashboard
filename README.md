# B2B Cold Calls Dashboard

A static GitHub Pages web app for the B2B Cold Calls Dashboard.

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Select branch `main` and folder `/root`, then click **Save**.
6. Your app will publish at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`.

## Important security note

This app currently uses a Google Sheets API key in the browser. Before publishing publicly, restrict the API key in Google Cloud Console to your GitHub Pages domain and only the Google Sheets API. Also make sure the Sheets are shared as **Anyone with link → Viewer** if the browser needs to read them.
