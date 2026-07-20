# Controlled Roundlet target policy

- This private repository exists only for bounded Roundlet forward testing.
- Preserve unrelated and unique work. Never force-push, reset, rebase, bypass protection, create releases or tags, or mutate another repository.
- Implementation issues may add or update only files under `fixtures/` unless an allowlisted owner comment explicitly changes scope.
- Use isolated `codex/` branches, reviewed pull requests, merge commits, and exact issue-closing references.

# roundlet:repository-authority
roundlet:
  enabled: true
  allow_mark_pr_ready: false
  allow_merge_pr: true
  allow_close_leaf_issue: true
  allow_delete_remote_branch: true
  allow_delete_local_branch: true
  allow_remove_worktree: true
# roundlet:end-repository-authority
