# List of PID and EBWOID issuers

## PID issuers
Country-specific issuers — issuing PID representing a particular Member State/jurisdiction.
> **Note:** *(test)* indicates that the organisation is not an officially appointed PID issuer, but can issue credentials for testing purposes within WE BUILD.


| Country     | Organisation      | Endpoint link | Wallet provider | ITB conformance | Trust list registered |
|-------------|-------------------|---------------|-----------------|--------------|-------------------------|
| Norway      | DigDir            | [Issuance endpoint](https://bevisporten.test.eidas2sandkasse.net/start-issuance?credential_configuration_id=no.digdir.eudiw.webuild.pid_sd_jwt_vc) | Reference wallet |              | Ongoing |
| Sweden      | ? (test)       |               |                 |              | ? |
| Netherlands | KvK (test)        |               | [NL Wallet by KVK](https://wallet-connect.eu/?mode=personal&lang=en) |              | ✅|
| Germany     | ? (test)          |               |                 |              | |
| France      | Docaposte (test)  | not publicly accessible yet              | [Docaposte](https://webuild-consortium.github.io/wp4-qtsp-group/?id=docaposte) |              | ✅ |
| Moldova     | eGov              | https://wallet.dev.egov.md/rp-tester/credential-offer | evo |              | |
| Czechia     | Aricoma           | https://lsps.demo.eudiw.cz/pid-issuer | RI EUDIW | ✅ | ✅ |


### Generic PID test issuers
The following issuers can issue PID test credentials for multiple countries and are intended for interoperability and testing within WE BUILD.

| Organisation | Endpoint | Wallet provider | ITB conformance | Trust list |
| --- | --- | --- | --- | --- |
|  eGov              | https://wallet.dev.egov.md/rp-tester/credential-claims | evo                |              | |
| Docaposte         | not publicly accessible yet              | [Docaposte](https://webuild-consortium.github.io/wp4-qtsp-group/?id=docaposte) |              | |

<br><br>
## EBWOID issuers
Country-specific issuers — issuing EBWOID representing a particular Member State/jurisdiction.
> **Note:** *(test)* indicates that the organisation is not an officially appointed PID issuer, but can issue credentials for testing purposes within WE BUILD.

| Country     | Organisation      | Endpoint link | Wallet provider | ITB conformance | Trust list registered |
|-------------|-------------------|---------------|-----------------|--------------|-------------------------|
| Norway      | BRC               | https://login.test.idporten.no/authorize/selector              |                 |              |  |
| Sweden      | Bolagsverket      | not publicly accessible yet               | [iGrant.io](https://webuild-consortium.github.io/wp4-wallets-group/?id=52)          |              | ✅ |
| Netherlands | KvK               |               | [NL Wallet by KVK](https://wallet-connect.eu/?mode=personal&lang=en) |              | ✅ |
| Germany     | Bundesanzeiger    | https://eida-issuer.spherity.dev/attested-issuance              | [Spherity](https://webuild-consortium.github.io/wp4-wallets-group/?id=75) |              | ✅ |
| France      | Infogreffe         |               | [Docaposte](https://webuild-consortium.github.io/wp4-qtsp-group/?id=docaposte) |              | ✅ |
| Moldova     | eGov              | https://wallet.dev.egov.md/rp-tester/credential-offer | evo |              | Ongoing |


### Generic EBWOID test issuers
The following issuers can issue EBWOID test credentials for multiple countries and are intended for interoperability and testing within WE BUILD.
| Organisation | Endpoint | Wallet provider | ITB conformance | Trust list |
| --- | --- | --- | --- | --- |
|  eGov              | https://wallet.dev.egov.md/rp-tester/credential-claims | evo                |              | |
| Docaposte         | not publicly accessible yet              | [Docaposte](https://webuild-consortium.github.io/wp4-qtsp-group/?id=docaposte) |              | |

