****Project Description****

A DNN (DotNetNuke) Search and Replace module.

This tool allows you to search (and optionally replace) text within any table in the DotNetNuke database.

Given the nature of this tool, only super (a.k.a. 'host') users are allowed to access its functionality.

You can perform search and replace operation in one or many of the configured targets. A 'target' is a database table/column pair.

A typical usage of this module is to update legacy Urls (or any text) embed in HTML modules or DNN Url's references. For example, after moving a DNN web site to a different URL.

The search will be case sensitive depending on your database configuration (the database collation). Typically (by default), it is case-insensitive.

The search will look for the given string on the select table/column, and will match with a 'contains...' criteria.

An empty 'Replace With' is valid. Therefore, you can 'delete' text.

Please find more information, screenshots, etc. at http://www.evotiva.com/Products/DNN-Search-And-Replace


DNNSearchAndReplace is based on the old 'aspx' tool (which is still available at http://www.evotiva.com/Downloads), but with many enhancements and packed as a DNN module. 

This module requires DotNetNuke 7.0.5 or later.
The single-page ASPX tool can be run on any DotNetNuke version. 
