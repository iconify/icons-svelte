<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mybb4febo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:ios-arrow-ltr-24-regular" {...props}></Icon>
<style>
:global(.mybb4febo) {
  fill: currentColor;
  d: path("m4.296 12l8.492-8.727a.75.75 0 1 0-1.075-1.046l-9 9.25a.75.75 0 0 0 0 1.046l9 9.25a.75.75 0 1 0 1.075-1.046z");
}

</style>
