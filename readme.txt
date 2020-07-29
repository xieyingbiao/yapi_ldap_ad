config.json

{
  "port": "3000",
  "adminAccount": "admin@admin.com",
  "db": {
    "servername": "mongo",
    "DATABASE": "yapi",
    "port": 27017
        },
   "ldapLogin": {
      "enable": true,
      "server": "ldap://172.16.61.198",
      "baseDn": "pan\\xieyingbiao",
      "bindPassword": "xyb123456",
      "searchDn": "DC=pan,DC=com",
      "searchStandard": "&(sAMAccountName=%s)",
      "emailPostfix": "",
      "emailKey": "",
      "usernameKey": "sAMAccountName"
  }
 }
