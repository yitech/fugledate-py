# fugledata
No description provided (generated by Openapi Generator https://github.com/openapitools/openapi-generator)

This Python package is automatically generated by the [OpenAPI Generator](https://openapi-generator.tech) project:

- API version: 12.2.3
- Package version: 1.0.0
- Generator version: 7.9.0
- Build package: org.openapitools.codegen.languages.PythonClientCodegen

## Requirements.

Python 3.7+

## Installation & Usage
### pip install

If the python package is hosted on a repository, you can install directly using:

```sh
pip install git+https://github.com/yitech/fugledata-py.git
```
(you may need to run `pip` with root permission: `sudo pip install git+https://github.com/yitech/fugledata-py.git`)

Then import the package:
```python
import fugledata
```

### Setuptools

Install via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install --user
```
(or `sudo python setup.py install` to install the package for all users)

Then import the package:
```python
import fugledata
```

### Tests

Execute `pytest` to run the tests.

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```python

import fugledata
from fugledata.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:3000
# See configuration.py for a list of all supported configuration parameters.
configuration = fugledata.Configuration(
    host = "http://localhost:3000"
)



# Enter a context with an instance of the API client
with fugledata.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = fugledata.IntrospectionApi(api_client)

    try:
        # OpenAPI description (this document)
        api_instance.root_get()
    except ApiException as e:
        print("Exception when calling IntrospectionApi->root_get: %s\n" % e)

```

## Documentation for API Endpoints

All URIs are relative to *http://localhost:3000*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*IntrospectionApi* | [**root_get**](docs/IntrospectionApi.md#root_get) | **GET** / | OpenAPI description (this document)
*AlembicVersionApi* | [**alembic_version_delete**](docs/AlembicVersionApi.md#alembic_version_delete) | **DELETE** /alembic_version | 
*AlembicVersionApi* | [**alembic_version_get**](docs/AlembicVersionApi.md#alembic_version_get) | **GET** /alembic_version | 
*AlembicVersionApi* | [**alembic_version_patch**](docs/AlembicVersionApi.md#alembic_version_patch) | **PATCH** /alembic_version | 
*AlembicVersionApi* | [**alembic_version_post**](docs/AlembicVersionApi.md#alembic_version_post) | **POST** /alembic_version | 
*BalanceApi* | [**balance_delete**](docs/BalanceApi.md#balance_delete) | **DELETE** /balance | 
*BalanceApi* | [**balance_get**](docs/BalanceApi.md#balance_get) | **GET** /balance | 
*BalanceApi* | [**balance_patch**](docs/BalanceApi.md#balance_patch) | **PATCH** /balance | 
*BalanceApi* | [**balance_post**](docs/BalanceApi.md#balance_post) | **POST** /balance | 
*InventoryApi* | [**inventory_delete**](docs/InventoryApi.md#inventory_delete) | **DELETE** /inventory | 
*InventoryApi* | [**inventory_get**](docs/InventoryApi.md#inventory_get) | **GET** /inventory | 
*InventoryApi* | [**inventory_patch**](docs/InventoryApi.md#inventory_patch) | **PATCH** /inventory | 
*InventoryApi* | [**inventory_post**](docs/InventoryApi.md#inventory_post) | **POST** /inventory | 
*KlineApi* | [**kline_delete**](docs/KlineApi.md#kline_delete) | **DELETE** /kline | 
*KlineApi* | [**kline_get**](docs/KlineApi.md#kline_get) | **GET** /kline | 
*KlineApi* | [**kline_patch**](docs/KlineApi.md#kline_patch) | **PATCH** /kline | 
*KlineApi* | [**kline_post**](docs/KlineApi.md#kline_post) | **POST** /kline | 
*MarketMetadataApi* | [**market_metadata_delete**](docs/MarketMetadataApi.md#market_metadata_delete) | **DELETE** /market_metadata | 
*MarketMetadataApi* | [**market_metadata_get**](docs/MarketMetadataApi.md#market_metadata_get) | **GET** /market_metadata | 
*MarketMetadataApi* | [**market_metadata_patch**](docs/MarketMetadataApi.md#market_metadata_patch) | **PATCH** /market_metadata | 
*MarketMetadataApi* | [**market_metadata_post**](docs/MarketMetadataApi.md#market_metadata_post) | **POST** /market_metadata | 


## Documentation For Models

 - [AlembicVersion](docs/AlembicVersion.md)
 - [Balance](docs/Balance.md)
 - [Inventory](docs/Inventory.md)
 - [Kline](docs/Kline.md)
 - [MarketMetadata](docs/MarketMetadata.md)


<a id="documentation-for-authorization"></a>
## Documentation For Authorization

Endpoints do not require authorization.


## Author




