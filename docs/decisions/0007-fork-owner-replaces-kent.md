# 0007: The fork's owner decides where Kent did

Status: accepted Date: 2026-11-18

## Decision

This repo is yixinsamgong's fork of `kentcdodds/mediarss`. Wherever an earlier
record ([0002](0002-never-edit-applied-migrations.md),
[0003](0003-public-urls-are-a-contract.md),
[0004](0004-media-files-are-read-only-by-default.md)) names Kent as the person
who approves, decides, or owns the data, read it as the fork's owner,
yixinsamgong. The rules in those records stay the same; only who makes the call
changes. Agents park high-risk and `needs-decision` work for the owner.

## Why

Those records were written for Kent's deployment. Editing them would rewrite
history, and the fork needs one named decider so agents know whom to wait for.

## Revisit if

The fork changes owner, gains more maintainers, or merges back into upstream.
