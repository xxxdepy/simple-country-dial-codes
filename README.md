# Simple Country Dial Codes
Dead simple JSON data file for country dial codes. 

### Why?
One problem I faced at the time of implementing a very simple and common feature, a country dial code selection, there are tons of repositories you can find with all the information about every country on this planet and that is where the problem was, it had a lot of information, more than we would ever need. 


It was difficult to find an accurate list of dial codes anywhere and in frustration I created this. 


### What's inside? 

For now the aim is to keep it lightweight and simple for you to use. It has the three basic information for all the countries with dial codes. Yes, any country that didn't have any dial codes isn't listed. 

    [ 
        {
            "name": "United States of America",
            "code": "US",
            "callingCode": "1" 
        },
        {
            "name": "United Kingdoms",
            "code": "GB", 
            "callingCode": "44" 
        },
        ...
    ]


**Countries with multiple calling codes**

For example there are three dialing codes for the country ["+1-809", "+1-829", "+1-849"] and based on this there are three different objects in the JSON file instead of keeping just one object with the three calling codes as an array.

    [ 
        {
            "name": "Dominican Republic",
            "code": "DO",
            "callingCode": "1809" 
        },
        {
            "name": "Dominican Republic",
            "code": "DO", 
            "callingCode": "1829" 
        },
        ...
    ]



##### Credits
Thanks to mledoze for https://github.com/mledoze/countries

The data is dependent on the data being provided on mledoze's repo. If you find any information that you think needs attention please also feel free to notify about it on their repo. 

Thanks!


