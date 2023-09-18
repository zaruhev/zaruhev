Hi, I'm Sarah. I code sometimes.

Before you ask: [Adding locally hosted code to GitHub](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github)

And because I keep forgetting:
```sh
# Get auth token from GitHub (this changes sometimes, just Google it).
echo "https://<username>:<token>@github.com" > ~/.git-credentials
git config --global credential.helper store
```

And because *you* keep forgetting:
> "How do I reset my local commit? D:"
```sh
git reset HEAD~
```
