# RJ's Plugin/Devlopment Collection

### Updating Modules To Latest
If you happen to need the latest module, clone this repository and run the following commands in Git Shell under the cloned repository:
git pull --recurse-submodules
git submodule update --remote --recursive
git submodule update --remote --merge

OPTIONAL (this will add the changes to the online repository):
git add .
git commit -m "Updated module(s) to latest"
git push