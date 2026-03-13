# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub profile repository** (`yongwoon/yongwoon`). The README.md is automatically displayed on the GitHub profile page at https://github.com/yongwoon.

## Structure

- `README.md` — The profile page content (bio, tech stack, featured projects, GitHub stats)
- `.github/workflows/profile-summary-cards.yml.yml` — GitHub Action that regenerates profile summary cards every 24 hours using `github-profile-summary-cards`

## Key Notes

- There is no build system, tests, or application code — this is a content-only repository
- The README uses shield.io badges extensively for visual tech stack display
- The GitHub Action requires a `SUMMARY_CARDS_TOKEN` secret configured in repo settings
- The workflow file has a double `.yml.yml` extension (likely unintentional)
- Profile owner: Yongwoon Kim, based in Tokyo, works across Korean/Japanese/English
