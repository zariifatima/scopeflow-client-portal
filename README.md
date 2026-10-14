# ScopeFlow — Client Request & Approval Portal

ScopeFlow is a responsive portfolio project that demonstrates a practical workflow for managing client change requests, effort estimates, delivery impact, and approval decisions.

## Features
- Overview dashboard and status metrics
- Create, view, edit, search, filter, and delete requests
- Estimate additional cost from hours × hourly rate
- Pending, Approved, Rejected, and In progress workflow
- Priority and requested delivery date fields
- Activity log for changes in the demo workspace
- Export requests to CSV
- Light and dark themes
- Responsive layout for desktop, tablet, and mobile
- Sample data and persistence using browser `localStorage`
- No framework, API key, or build step required

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Upload the files in this project to the **root** of your `scopeflow-client-portal` repository.
2. Open the repository on GitHub and select **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose branch **main** and folder **/(root)**, then save.
5. Wait for GitHub Pages to publish and open the URL shown on the Pages settings page.

## Demo limitations
This is a frontend-only portfolio demo, not a production multi-user service. It has no login, backend API, shared database, email notifications, or role-based access control. Data stays in the current browser and device; clearing browser storage can erase it. Do not enter confidential client information.

## Possible future improvements
- Backend API and persistent database
- Authentication and client/team roles
- Server-side audit trail and notifications
- Automated UI tests and continuous integration

## Technology
HTML, CSS, vanilla JavaScript, `localStorage`, and the browser Blob API for CSV export.

## License
MIT. See [LICENSE](LICENSE).
