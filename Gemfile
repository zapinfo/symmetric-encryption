eval File.read(File.expand_path('../gemfiles/Gemfile.common.rb', __FILE__)), nil, 'Gemfile.common.rb'

gem 'activerecord', '>= 5.0.0.rc1'
gem 'activemodel-serializers-xml', require: 'active_model/serializers'

# Also test MongoMapper
gem 'mongo_ha'
gem 'mongo_mapper'
gem 'bson_ext', platform: :ruby

gemspec
