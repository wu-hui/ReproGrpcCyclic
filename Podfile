source 'https://github.com/CocoaPods/Specs.git'

use_frameworks!

platform :ios, '11.0'
inhibit_all_warnings!

target 'NewSwiftApp' do
  pod 'gRPC-C++', '~> 1.57.0'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    puts target.name
  end
end
