# frozen_string_literal: true

require_relative "lib/PLACEHOLDER/config/version"

Gem::Specification.new do |spec|
  spec.name    = "PLACEHOLDER"
  spec.version = PLACEHOLDER::Config::VERSION
  spec.authors = ["yurigitsu"]
  spec.email   = ["PLACEHOLDER EMAIL"]
  spec.license = "MIT"

  spec.required_ruby_version = ">= 3.0.0"

  spec.summary     = "PLACEHOLDER SUMMARY"
  spec.description = "PLACEHOLDER DESCRIPTION"
  spec.homepage    = "https://github.com/yurigitsu/" + spec.name
  
  spec.files  = Dir["CHANGELOG.md", "LICENSE", "README.md", "PLACEHOLDER.gemspec", "lib/**/*"]
  
  spec.bindir        = "bin"
  spec.executables   = []
  spec.require_paths = ["lib"]

  spec.metadata["repo_homepage"]     = "https://github.com/yurigitsu/"
  spec.metadata["allowed_push_host"] = "https://rubygems.org"
  
  spec.metadata["homepage_uri"]    = spec.homepage
  spec.metadata["changelog_uri"]   = spec.homepage + "/blob/main/CHANGELOG.md"
  spec.metadata["source_code_uri"] = spec.homepage
  spec.metadata["bug_tracker_uri"] = spec.homepage + "/issues"

  spec.add_runtime_dependency "PLACEHOLDER_1", "~> PLACEHOLDER_1_VERSION"
  spec.add_runtime_dependency "PLACEHOLDER_2", "~> PLACEHOLDER_2_VERSION"

  spec.add_development_dependency "bundler"
  spec.add_development_dependency "rake"
  spec.add_development_dependency "rspec"
  spec.add_development_dependency "pry"
end
