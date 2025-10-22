# 2025techpro_Session2
Git Installation

## Install Git
Download and install the latest version of Git ---> https://git-scm.com/downloads<br>
## Set up Git 
Setting your Git username for every repository on your computer <br>

Open Terminal.<br>

Set a Git username:  <br>
`git config --global user.name "YOUR USERNAME"`<br>

Confirm that you have set the Git username correctly:  <br>
`git config --global user.name`<br>


Setting your email address for every repository on your computer <br>

Open Terminal.<br>

Set an email address in Git  <br>
`git config --global user.email "YOUR_EMAIL" `<br>

Confirm that you have set the email address correctly in Git:  <br>
`git config --global user.email `  <br>
## Basic Commands  <br>

Open terminal  <br>

Check your version  <br>
`git --version  `<br>
List all settings<br>
`git config --list`<br>
Uset from Configuration<br>
`git config --global --unset`<br>
Set Default Values<br>
`git config --global init.defaultBranch main`<br>

##Start a project<br>
`mkdir myproject`<br>
`cd myproject`<br>
`ls -a`<br>
`git init `<br>
`ls -a`<br>
`vi index.html`<br>
Add code from index.html in this repository  <br>
Search the web how you can save and exit vi  <br>
`ls`<br>
`git status` <br>
`git add index.html`<br>
`git status`<br>
`git commit -m "I commit, Do you Commit?"`<br>
`git status`<br>


