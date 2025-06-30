---
#https://www.notion.so/n8n/Frontmatter-432c2b8dff1f43d4b1c8d20075510fe4
contentType: overview
---


# Trigger Nodes

[Triggers nodes](/glossary.md#trigger-node-n8n) are the **starting point** of any workflow in n8n.

Unlike other nodes:
- They don’t have inputs,
- They display a lightning bolt icon,
- They have a rounded left edge.

There are many available trigger nodes in n8n. The most common trigger types are:
- Manual Trigger: Start manually for testing.
- Schedule Trigger: Run periodically.
- Webhook Trigger: Respond to HTTP requests.
- App-specific Triggers: e.g., PipeDrive, Google Drive, etc.
- User Triggers: Via chat or form inputs.
- Error Trigger: When another workflow fails.

There are two ways to run triggers:
* Manual Execution: While building your workflow, you can always run any trigger manually. This is very helpful for debugging.
* Production Execution: Once your workflow is tested and ready, you can put it in "Production" mode by switching the "Active" button at the top of the interface. From then on, your workflow will run on its own, depending on your trigger settings.

Past workflow executions are stored in the "Execution" tab.

## How to Use Trigger Nodes

1. Begin a new workflow.
2. Open the Nodes Panel, and type "trigger" in the search box.
3. Scroll down to a trigger that you want to use (ie. "Manual Trigger").
4. Click the trigger: n8n will add it to your workflow.
5. Click the "Execute workflow" button to start a test manually.

Open the "Execution" tab to confirm that n8n has indeed run the workflow following your click.

## Tips & Tricks

- Use "Manual Trigger" to run quick tests.
- You can have only one Manual Trigger per workflow.
- Use the "Execute Step" button to isolate a behavior.
- App-based triggers might use webhooks or polling.
- Custom Triggers require special implementation logic.

## Things to know

- Make sure you understand the difference between manual and production runs.
- App-based triggers might not be real-time.
- Custom trigger creation is possible; documentation is coming soon.
