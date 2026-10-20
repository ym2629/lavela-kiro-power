# lavela power for Kiro

Lets your Kiro agent deploy an app from a GitHub repository to a live server and check on it afterwards, by connecting Kiro to the lavela remote MCP server. lavela is in beta.

This repository contains configuration and one skill only. lavela's source code is not published here.

## Install

In Kiro, open **Add Custom Power**, choose **Import power from GitHub**, and enter:

```
https://github.com/ym2629/lavela-kiro-power
```

When Kiro opens your browser, sign in with your lavela account (OAuth). There is no token to paste.

## What it does

- Analyzes a GitHub repository and tells you how lavela would run it.
- Builds the app from the repository on a managed server and gives you a live URL.
- Shows the status, health and logs of a deployed app when you ask. lavela does not monitor your app on its own.
- Asks you before anything that costs money or deletes something. Adding funds always happens in your browser, never through the agent.

lavela never edits your source code. Payments setup depends on the countries the payment provider supports.

## Try it

- "Check my lavela account status."
- "Analyze this repo and tell me how lavela would deploy it: https://github.com/OWNER/REPO"
- "Deploy my GitHub repo OWNER/REPO and give me the live URL."
- "Is my app up? Show me the latest logs and errors."

## Privacy and support

- Privacy policy: https://console.lavela.dev/privacy · Terms: https://console.lavela.dev/terms
- This power sends nothing on its own. When you use it, your agent talks to the lavela MCP server you signed in to.
- Support: open an issue at https://github.com/ym2629/lavela-kiro-power/issues. More about the service: https://lavela.dev and https://console.lavela.dev/docs/mcp

License: MIT.
