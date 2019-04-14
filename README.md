# SGE-scripts

Some scripts for managing nodes and jobs on SGE

## snodes.v2

Snodes is a command-line tool for showing the current status of queues and available resources.

### Features:

* decorate the status of queues in different colors (free, partly used, full)

* highlight abnormal queues

* show the detailed informations of abnormal queues (reasons, affected users)

![snodes.v2](https://github.com/zengxiaofei/SGE-scripts/blob/master/screenshots/snodes.v2.png)

### Installation && Usage:

```bash
# clone the repo
$ git clone https://github.com/zengxiaofei/snodes.git
# run snodes.v2
$ ./snodes/snodes_v2/snodes.v2
```

## snodes.v1

Legacy version of snodes with some bugs. No more updates.
