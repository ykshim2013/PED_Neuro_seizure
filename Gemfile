source "https://rubygems.org"

# Jekyll version compatible with Cloudflare Pages
gem "jekyll", "~> 4.3"

# Theme - using remote theme for GitHub Pages compatibility
gem "jekyll-remote-theme"

# Required plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "kramdown-parser-gfm"
end

# Windows and JRuby compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock HTTP parser gem to avoid HTTP::Parser issues
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
