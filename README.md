# Freshly — Expiry Date Tracker

A responsive, no-install expiry tracker for food, skincare, medicine, household supplies, and more.

## Start

Open `index.html` in Chrome, Safari, Firefox, or Edge. Alternatively, run a local server in this folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Features

- Add, edit, and delete items with an expiry date, category, quantity, and notes.
- Automatic status: expired, expiring in 0–7 days, or safe.
- Dashboard counts, sidebar filters, category filter, search, and sorting.
- CSV export for backups or spreadsheets.
- Saves your items in **this browser's localStorage**, with no account or backend required.
- Responsive layout for phone and desktop.

## Data & limitations

Data is stored locally on one browser/device; clearing site data or opening another browser will not transfer items. Use **Export CSV** to back up your data. The app currently does not send push notifications, synchronize between devices, or import CSV. Counts update when you open or refresh the page. The starter inventory is empty so you can enter your own items.
