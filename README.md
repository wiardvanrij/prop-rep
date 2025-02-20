# Prop-rep

[![Maintainability](https://api.codeclimate.com/v1/badges/0d8492035cb7a262ef8b/maintainability)](https://codeclimate.com/github/AlexsJones/prop-rep/maintainability)

A golang command line tool to show you which organisations are contributing to a repository.

![demo](./images/demo.gif)

```
prop-rep scan -r prometheus/prom2json -v
17 contributors found
This will take a while...
17/17 Users scanned
24 unique organisations found
Organisation             Contributors  Users
prometheus               6             beorn7, SuperQ, simonpasquier, juliusv, discordianfish, roidelapluie
FOSDEM                   1             SuperQ
open-cluster-management  1             chaitanyaenr
voxpupuli                1             roidelapluie
noisetor                 1             SuperQ
```

## Dependencies

A `GITHUB_TOKEN` environment variable is required to access the GitHub API.
