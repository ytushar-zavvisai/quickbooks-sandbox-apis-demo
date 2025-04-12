# QuickBooks API Integration (Sandbox)

This guide walks you through how to authenticate with QuickBooks Online (sandbox environment) and run common accounting API calls (AR/AP, Company Info, Cash Flow, etc.) using Python and Jupyter Notebook.

---

## 🚀 Prerequisites

- QuickBooks Developer Account: https://developer.intuit.com/
- A Sandbox Company created in your developer dashboard - Done on QuickBooks
- Python environment (preferably Jupyter Notebook) - On your local machine
- Installed dependencies: - - On your local machine

```bash
pip install intuit-oauth requests
```


## ✅ Notes

- The authorization code can only be used **once** and expires within a few minutes.
- Always copy the latest `code` and `realmId` from the redirect URL.
- Use `refresh_token` to regenerate `access_token` if expired.
