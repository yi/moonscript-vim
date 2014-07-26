# moonscript-vim

Adds syntax highlighting and indent support for MoonScript in vim.

## Install

### Using [Vundle](https://github.com/gmarik/vundle)

1. Add the following to your `.vimrc` where other bundles are located:

		Bundle 'leafo/moonscript-vim'

2. Run from command line:

		$ vim +BundleInstall

### Using [pathogen](https://github.com/tpope/vim-pathogen)

1. Check out the repository into your bundle path:

        $ cd ~/.vim/bundle
        $ git clone git://github.com/leafo/moonscript-vim.git

### Normal

1. Check out the repository and copy the following to `.vim/` directory or any
   other run time path, keeping their directory structure intact:

		syntax/moon.vim
		indent/moon.vim
		ftdetect/moon.vim

## Support CoffeeTags on Tagbar

CoffeeTags works perfectly on MoonScript.
The CoffeeTags vim plugin has been mreged into this moonscript-vim.
You can install and enable CoffeeTags in Vim according to [this readme](https://github.com/lukaszkorecki/coffeetags)

## Thanks

Special thanks to the <https://github.com/kchmck/vim-coffee-script> project. I
copied the syntax and indent code as a starting point.
