# Vim Markdown Tags Plugin for MkDocs

`mkdocs-vim-md-tags-plugin` is a [plugin](plugins.md) for MkDocs that generates a vim tags file for autocompleting and navigating through markdown pages.

![mkdocs vim md tags demo](../images/mkdocs_vim_md_tags_demo.gif)

The above demo shows how the plugin can be used to rapidly develop wiki-style interconnected pages in a very organic way. While writing the `space` article, the author decides to link to a new article called `universe`, for which a file does not yet exist. So the author creates the file, and---as long as an instance of `mkdocs serve` is running in the background---the plugin generates a new tags file that includes `universe.md`, which the author can then navigate to and begin filling out the new article. 

This way of authoring pages allows for articles to be highly interconnected. The best time to contextually link between articles is while the content is being generated. No one is going to come back and link together pages after the fact. This plugin allows for these connections to be created in a very straightforward and easy manner.

This plugin takes advantage of vim's build in tag system. type `:help tags` while in vim for more information on tags. For the purposes of this plugin, the two most imporant keybindings to remember are:

## Keybindings

`Ctrl+]` - This command jumps to the tag underneath the cursor.

`Ctrl+t` - This command returns to the previous entry in the tag stack.


## Usage and Installation

Please visit the [github page](https://github.com/midnightprioriem/mkdocs-vim-md-tags-plugin) for installation and usage instructions.
