
<a name="v0.1.6"></a>
## [v0.1.6](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.1.5...v0.1.6) (2021-05-21)

### Chore

* added a variable to manage priority class name option for pods
* added a resources value to ingresscontroller to fix HPA

### Docs

* update readme with parameters

### Merge Requests

* Merge branch '25-insufficient-quota-to-match-these-scopes' into 'master'
* Merge branch '24-hpa-doesn-t-work-with-an-ingress-controller-solution' into 'master'


<a name="v0.1.5"></a>
## [v0.1.5](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.1.4...v0.1.5) (2021-03-02)

### Chore

* modify kong's version chart with changes that will configure about resources
* modify kong's version chart with changes that will configure about resources
* update changelog file
* update readme file and examples for proxy ingress host
* update Changelog
* update block of hostname in proxy ingress

### Docs

* update changelog file with v0.1.5
* update Changelog file
* update readme file with variables
* update VERSION

### Feat

* configure migrations block for kong chart
* configure variable to define custom registry

### Fix

* typo in variables
* conflict about variables

### Merge Requests

* Merge branch '22-release-v0-1-5' into 'master'
* Merge branch '22-release-v0-1-5' into 'master'
* Merge branch '22-release-v0-1-5' into 'master'
* Merge branch '21-added-a-variable-to-configure-a-custom-registry' into '22-release-v0-1-5'


<a name="v0.1.4"></a>
## [v0.1.4](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.1.3...v0.1.4) (2021-01-27)

### Docs

* update changelog
* fix examples

### Feat

* update version updating helm chart

### Fix

* update version helm chart for kong

### Merge Requests

* Merge branch '19-release-v0-1-4' into 'master'
* Merge branch '18-update-kong-chart-1-14-1' into 'master'


<a name="v0.1.3"></a>
## [v0.1.3](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.1.2...v0.1.3) (2020-12-22)

### Fix

* array

### Merge Requests

* Merge branch 'fix-array' into 'master'


<a name="v0.1.2"></a>
## [v0.1.2](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.1.1...v0.1.2) (2020-12-22)

### Chore

* enabled pullSecrets

### Merge Requests

* Merge branch 'pullsecrets' into 'master'


<a name="v0.1.1"></a>
## [v0.1.1](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.1.0...v0.1.1) (2020-12-08)

### Chore

* updated Kong resources

### Merge Requests

* Merge branch 'update-kong-version' into 'master'


<a name="v0.1.0"></a>
## [v0.1.0](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.0.7...v0.1.0) (2020-11-16)

### Chore

* update README with stable version of module
* update CHANGELOG
* update README
* update tag VERSION v0.1.0
* updating kong chart version to 1.11.0, also kong 2.2.0

### Merge Requests

* Merge branch '17-update-kong-chart-1-11-0' into 'master'
* Merge branch '17-update-kong-chart-1-11-0' into 'master'


<a name="v0.0.7"></a>
## [v0.0.7](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.0.6...v0.0.7) (2020-11-12)

### Chore

* update CHANGELOG
* update tag VERSION v0.0.7
* update README
* typo on variable
* formating files
* clean examples version for kong module
* added example with custom values for kong.conf
* added variable to set custom enviroment configurations in kong.yaml

### Merge Requests

* Merge branch '16-release-v0-0-7' into 'master'
* Merge branch '15-able-to-pass-extra-envs' into 'master'


<a name="v0.0.6"></a>
## [v0.0.6](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.0.5...v0.0.6) (2020-11-05)

### Chore

* update changelog
* update VERSION v0.0.6 tag
* update README , examples information with release
* added example using resources
* change resources variables for kong pod

### Merge Requests

* Merge branch '14-release-v0-0-6' into 'master'
* Merge branch '13-empty-all-request-and-limits-on-resources' into 'master'


<a name="v0.0.5"></a>
## [v0.0.5](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.0.4...v0.0.5) (2020-10-10)

### Chore

* update VERSION v0.0.5 tag
* init changelog
* update gitignore for changelog
* update README , examples information with release
* configure variable to pass extra values

### Merge Requests

* Merge branch '9-release-v0-0-5' into 'master'
* Merge branch '8-configure-extra-set-values' into 'master'


<a name="v0.0.4"></a>
## [v0.0.4](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.0.3...v0.0.4) (2020-10-09)

### Chore

* using variables for chart values in helm releases provider

### Merge Requests

* Merge branch '7-release-v0-0-4' into 'master'
* Merge branch '6-variable-on-helm-repository-value' into 'master'


<a name="v0.0.3"></a>
## [v0.0.3](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.0.2...v0.0.3) (2020-10-08)

### Chore

* fix typo on script
* fix a call null on script
* update makefile to use release.sh
* improve release.sh

### Merge Requests

* Merge branch '3-release-ci' into 'master'
* Merge branch '3-release-ci' into 'master'
* Merge branch '4-add-readme' into 'master'
* Merge branch '3-release-ci' into 'master'


<a name="v0.0.2"></a>
## [v0.0.2](https://gitlab.com/bennuteam/terraform-helm-kong/compare/v0.0.1...v0.0.2) (2020-10-08)

### Merge Requests

* Merge branch '5-test-release' into 'master'


<a name="v0.0.1"></a>
## v0.0.1 (2020-10-08)

### Merge Requests

* Merge branch '3-release-ci' into 'master'
* Merge branch '3-release-ci' into 'master'
* Merge branch '3-release-ci' into 'master'
* Merge branch '3-release-ci' into 'master'
* Merge branch '4-add-readme' into 'master'
* Merge branch '2-build-examples' into 'master'
* Merge branch '1-kong-module' into 'master'

