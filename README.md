# Artifactory Sample User Plugins


> JFrog Workers is the newer, recommended way to easily extend the JFrog Platform (not just Artifactory) in a cloud-native way. While plugins are supported, we strongly suggest using JFrog Workers whenever possible. [Learn more](https://jfrog.com/help/r/ybbUNZGwwAmzW2qGyL9Zdw/I4E5sOhWWpIHHfdV37__Iw)

## Upgrade Notice

#### 1. Artifactory Plugins Upgraded to Groovy 4 in Artifactory Version *7.101.0*. Please note that the promotion plugin has been upgraded in order to be compatible with Groovy version upgrade. Upgrading this plugin requires moving to Groovy 4, which may also affect User Plugins. Which Branch to use? ####
* **master** Artifactory Version 7.101.0 & above
* **artifactory-java-lower-than-21** Artifactory version 7.100.0 & below

#### 2. Many of the artifactory user plugins are no longer compatible with the recent versions of Artifactory particularly after *JDK17* support introduced in **7.43** and above.These deprecated plugins have been moved to the [deprecated directory](http://github.com/jfrog/artifactory-user-plugins/tree/master/deprecated-plugins).


## General Information
* [Artifactory Documentation](https://jfrog.com/help/p/devops-home)
* [User Plugin Documentation](https://jfrog.com/help/r/jfrog-integrations-documentation/user-plugins)
* [Worker Documentation](https://jfrog.com/help/r/ybbUNZGwwAmzW2qGyL9Zdw/I4E5sOhWWpIHHfdV37__Iw)

## Worker alternative for plugins
> Currently worker are support only for Enterprise X & plus licenece 

| User Plugin | Worker |
| ----------- | ----------- |
| [ArtifactCleanup](https://github.com/jfrog/artifactory-user-plugins/tree/master/backup/backupFolders) | [ArtifactCleanup Sample](https://github.com/jfrog/workers-sample/tree/main/samples/artifactory/GENERIC_EVENT/artifact-cleanup)  |
| [backUpFolder](https://github.com/jfrog/artifactory-user-plugins/blob/master/backup/backupFolders/README.md) | X |
| [promotions](https://github.com/jfrog/artifactory-user-plugins/blob/master/build/promotion/README.md) | X |
| [checksums](https://github.com/jfrog/artifactory-user-plugins/blob/master/checksums/README.md) | X |
| [cleanDockerImages](https://github.com/jfrog/artifactory-user-plugins/blob/master/cleanup/cleanDockerImages/README.md) | [cleanDockerImages Sample](https://github.com/jfrog/artifactory-user-plugins/blob/master/cleanup/cleanDockerImages/README.md) |
| [deleteByPropertyValue](https://github.com/jfrog/artifactory-user-plugins/blob/master/cleanup/deleteByPropertyValue/README.md) | [deleteByPropertyValue Sample](https://github.com/jfrog/workers-sample/blob/main/samples/artifactory/GENERIC_EVENT/delete-by-property-value/README.md) |
| [deleteDeprecatedPlugin](https://github.com/jfrog/artifactory-user-plugins/blob/master/cleanup/deleteDeprecated/README.md) | X |
| [deleteEmptyDirsPlugin](https://github.com/jfrog/artifactory-user-plugins/blob/master/cleanup/deleteEmptyDirs/README.md) | [deleteEmptyDirsPlugin Sample](https://github.com/jfrog/workers-sample/blob/main/samples/artifactory/GENERIC_EVENT/delete-empty-dirs/README.md) |
| [mavenSnapshotCleanupWhenRelease](https://github.com/jfrog/artifactory-user-plugins/blob/master/cleanup/mavenSnapshotCleanupWhenRelease/README.md) | X |
| [cleanOldBuilds](https://github.com/jfrog/artifactory-user-plugins/blob/master/cleanup/oldBuildCleanup/README.md) | X |
| [remoteBackup](https://github.com/jfrog/artifactory-user-plugins/blob/master/storage/remoteBackup/README.md) | [remoteBackup Sample](https://github.com/jfrog/workers-sample/blob/main/samples/artifactory/GENERIC_EVENT/remote-backup/README.md) |
| [repoQuota](https://github.com/jfrog/artifactory-user-plugins/blob/master/storage/repoQuota/README.md) | [repoQuota Sample](https://github.com/jfrog/workers-sample/blob/main/samples/artifactory/BEFORE_UPLOAD/repo-quota/README.md) |
| [restrictOverwrite](https://github.com/jfrog/artifactory-user-plugins/blob/master/storage/restrictOverwrite/README.md) | [restrictOverwrite Sample](https://github.com/jfrog/workers-sample/blob/main/samples/artifactory/BEFORE_UPLOAD/restrict-overwrite/README.md) |
| [repoStats](https://github.com/jfrog/artifactory-user-plugins/blob/master/stats/repoStats/README.md) | [repoStats Sample](https://github.com/jfrog/workers-sample/blob/main/samples/artifactory/GENERIC_EVENT/repoStats/README.md) |
| [preventUnapproved](https://github.com/jfrog/artifactory-user-plugins/blob/master/governance/preventUnapproved/README.md) | X |
| [getP2Urls](https://github.com/jfrog/artifactory-user-plugins/blob/master/config/getAndSetP2Url/README.md) | X |
| [getPropertySetsList](https://github.com/jfrog/artifactory-user-plugins/blob/master/config/propertySetsConfig/README.md) | X |
| [getProxiesList](https://github.com/jfrog/artifactory-user-plugins/blob/master/config/proxiesConfig/README.md) | X |
| [getLayoutsList](https://github.com/jfrog/artifactory-user-plugins/blob/master/config/repoLayoutsConfig/README.md) | X |



## Contributing to Artifactory User plugin
> JFrog Workers is the newer, recommended way to easily extend the JFrog Platform (not just Artifactory) in a cloud-native way. So limited feature request are considered on user plugin<br/>

For more complete instructions on contributing to Artifactory user plugin, please see [CONTRIBUTING.md](CONTRIBUTING.md).

## Copyright and License Information
Copyright &copy; 2011, JFrog Ltd.
