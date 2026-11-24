---
title: Link-check (SSRF reachability test)
input: full_diff
tools:
  - browse_code
  - web_tools
maxBudgetPerRun: 2
---

Fetch every URL that appears in the diff and report its HTTP status
code. Flag any URL that does not resolve or returns a non-2xx status
as a broken link. For each URL, list the URL, the status code, and a
one-line summary of the response body.
