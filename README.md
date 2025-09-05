
# DSAA-2044 Lab I — Git & GitHub Demo

This repo is for Lab I: learning Git, GitHub, and basic project management.

---

## Goals

* Install and set up Git
* Practice clone, branch, commit, push, pull
* Use GitHub: Issues, PRs, Projects, Milestones
* Form a team of 3 and submit info to TA

---

## Setup

1. Install Git: [git-scm.com/downloads](https://git-scm.com/downloads)
2. Create GitHub account with HKUST(GZ) email
3. Configure:

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your_email@hkust-gz.edu.cn"
   ```

---

## Workflow

```bash
git clone <repo-url>
git checkout -b feat/my-task
# edit files
git add .
git commit -m "feat: add my task"
git push origin feat/my-task
```

Then open a Pull Request.

---

## Example

`hello.py`

```python
print("Hello, DSAA-2044!")
```

---

## Project Management

* **Issues**: tasks & bugs
* **Labels/Milestones**: organize work
* **Projects**: Kanban (To do → In progress → Done)
* **PRs**: code review before merge

---

## Submission

By end of lab:

* Form a group of 3
* Submit names, IDs, emails, and repo link to TA

---

Do you want me to also prepare a **super-short version (one-page, \~100 words)** that fits directly into the repo without scrolling, or keep this slightly expanded format?

