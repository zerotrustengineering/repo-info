# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [CLI Method for RPM](#cli-method-for-rpm)
    - [Download and Import GPG Key](#download-and-import-gpg-key)
    - [Configure the Yum Repo](#configure-the-yum-repo)

## Description

Call us old fashioned, but we like to package up software via tried and true
Enterprise Linux delivery method... Signed RPMs

## CLI Method for RPM

### Download and Import GPG Key

```bash
sudo wget https://github.com/zerotrustengineering/repo-info/gpgkey/RPM-GPG-KEY-zerotrustengineering.com -o /etc/pki/rpm-gpg/RPM-GPG-KEY-zerotrustengineering
sudo rpm --import /etc/pki/rpm-gpg/RPM-GPG-KEY-zerotrustengineering
```

### Configure the Yum Repo

Packages and repo information is available for our paying customers.
