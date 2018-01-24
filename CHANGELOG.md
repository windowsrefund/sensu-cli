## 0.9.1 01/24/2018
* Add --format to silenced list

## 0.9.0 01/18/2018
* Add token authorization

## 0.8.1 07/27/2017
* Updating Rainbow version for dependency chains

## 0.8.0 07/27/2017
* Add support for new silenced API version 0.26+
* If not specified creator will detect on OSX and Linux from whoami

## 0.7.1 06/23/2015
* Rainbow compatability

## 0.7.0 06/09/2015
* Add Socket create and raw command
* Add api_endpoint to config for people proxying to a different api endpoint
* Relax mixlib-config requirements

## 0.6.3 10/08/2014
* Remove item count from json output

## 0.6.2 08/20/2014
* Fix path to events template bug

## 0.6.1 08/08/2014
* Fix proxy address causing http request failing

## 0.6.0 07/29/2014
* Added settings for proxies
* Support for 0.13 event data --format table and single have new template (use sensu-cli 0.5.0 for previous sensu versions)

## 0.5.0 05/10/2014
* Deep Filtering in responses
* Added filtering to event, stash, check and aggregate

## 0.4.0 05/06/2014
* Added Bash Completion
* Added Client filtering option
* Added ability to turn off colored output
* Updated rainbow gem
* Updated mixlib config gem
* Cleanup for updated rubocop

## 0.3.1 12/11/2013
* Added read and connect timeouts to config
* Fix silence payload

## 0.3.0 10/29/2013
* Sensu 0.12.0 compliance release
* 10292013 Update to new expire logic for stashes
* 10292013 Update deprecated check/request and event/resolve endpoints

## 0.2.5 10/24/2013
* 10242013 fix text in silence option for cli
* 10042013 added owner to silence

## 0.2.4 08/09/2013
* 07052013 added formats to stashes
* 07052013 added json to formats for event, client and stash list
* 08092013 removed ruby-terminfo as it has issues on RHEL.  Replaced with a built in Hirb method.

## 0.2.3
* 07032013 added a table format for events and clients
* 07042013 fully passing rubocop lint tests
* 07042013 added ability to pass in fields for client table -f table -F name,address,subscriptions

## 0.2.2
* 07032013 added a header to identify for proxying requests
* 07032013 initial lint cleanup from rubocop

## 0.2.1
* 07032013 added a single line format for events and clients
