# Using the Brand API of Brandfetch #
Brandfetch's brand API allows developers to obtain programmatic access to a company's visual assets, such as logos, colors, and fonts. This can be useful for building applications that require consistent branding across various organizations.



[Brand API](https://www.worldindata.com/api/Brandfetch-brand-api)

The Worldindata API marketplace presents a variety of third party APIs, with the goal of simplifying the way users interact with data. This can make it easier for individuals and businesses to find and use the information they need.

## Clients, Industry, and Sectors for the API ##

**Industry and Sectors**
- e-commerce
- marketing
- marketplace
- brand analysis
- competition analysis
- and more

**Client Types**
- e-commerce platforms
- web scrapers
- product comparison websites
- online shopping platforms
- consumer analysts
- product analysis
- competition intelligence
- business intelligence
- and more




## Objects, Parameters and JSON output ##
The GET /v2/brands/ endpoint is a key part of the Brandfetch brand details API, allowing users to retrieve detailed information about a specific brand.


**filter parameters**
- domain


```
{
  "name": "brandfetch",
  "domain": "brandfetch.com",
  "claimed": true,
  "description": "The Brand Search Engine",
  "links": [
    {
      "name": "twitter",
      "url": "https://twitter.com/@Brandfetch"
    },
    {
      "name": "linkedin",
      "url": "https://linkedin.com/company/brandfetch"
    }
  ],
  "logos": [
    {
      "type": "icon",
      "theme": null,
      "formats": [
        {
          "src": "https://asset.development.brandfetch.io/idu_9vNjbv/idHyMcMCbY.png",
          "background": null,
          "format": "png",
          "height": 400,
          "width": 400,
          "size": 2565
        }
      ]
    },
    {
      "type": "logo",
      "theme": null,
      "formats": [
        {
          "src": "https://asset.development.brandfetch.io/idu_9vNjbv/idjBwaQU_z.png",
          "background": "transparent",
          "format": "png",
          "height": 215,
          "width": 800,
          "size": 33937
        },
        {
          "src": "https://asset.development.brandfetch.io/idu_9vNjbv/idQVdMqLoj.svg",
          "background": "transparent",
          "format": "svg",
          "size": 15567
        }
      ]
    }
  ],
  "colors": [
    {
      "hex": "#242c54",
      "type": "asset",
      "brightness": 45
    },
    {
      "hex": "#ffffff",
      "type": "asset",
      "brightness": 255
    },
    {
      "hex": "#5eabea",
      "type": "asset",
      "brightness": 159
    }
  ],
  "fonts": [
    {
      "name": "Poppins",
      "type": "asset",
      "origin": "google",
      "originId": "Poppins",
      "weights": []
    },
    {
      "name": "Roboto",
      "type": "asset",
      "origin": "google",
      "originId": "Roboto",
      "weights": []
    }
  ],
  "images": [
    {
      "type": "banner",
      "formats": [
        {
          "src": "https://asset.development.brandfetch.io/idu_9vNjbv/idp4T5qIAz.png",
          "background": "transparent",
          "format": "png",
          "height": 500,
          "width": 1500,
          "size": 5539
        }
      ]
    }
  ]
}

```
**Objects**
- name
- domain
- claimed
- description
- links*
- links.name
- links.url
- logos
- logo.type
- logo.theme
- logo.formats
- logo.formats.src
- logo.formats.background
- logo.formats.format
- logo.formats.height
- logo.formats.width
- logo.formats.size
- colors
- colors.hex
- colors.type

## Software Development Kit ##
Software Development Kits (SDKs) are available for the Brandfetch brand details database in a variety of programming languages, including JAVA, Python, PHP, and Ruby. These SDKs make it easy for developers to integrate Brandfetch's data into their applications.


### Disclaimer of liability ###

Worldindata is not the owner of the data contained within its API marketplace, but rather a facilitator that aims to make the data more accessible and user-friendly. We are big fans of the Brandfetch brand API and the valuable insights it provides. Note that the availability of data on Worldindata is subject to change and may be removed at any time at the discretion of the data provider.

[Worldindata](https://www.worldindata.com)
