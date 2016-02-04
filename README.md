run-docker-stuff
================

Small script to run various commands in Docker containers, using the current working directory.


Usage
-----

```bash
~/run-docker-stuff/run-docker-stuff --help
~/run-docker-stuff/run-docker-stuff --list-aliases
~/run-docker-stuff/run-docker-stuff --add-alias old-npm="node:0.10 npm"
~/run-docker-stuff/run-docker-stuff --add-alias old-node="node:0.10 node"
~/run-docker-stuff/run-docker-stuff --link-aliases
old-npm install
old-node my-script.js
```
