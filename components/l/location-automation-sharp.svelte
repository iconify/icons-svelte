<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc3u524mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:location-automation-sharp" {...props}></Icon>
<style>
:global(.jc3u524mk) {
  fill: currentColor;
  d: path("M4 19V7l8-6l8 6v4h-2V8l-6-4.5L6 8v9h6v2Zm14.5 3l-1.4-3.1l-3.1-1.4l3.1-1.4l1.4-3.1l1.4 3.1l3.1 1.4l-3.1 1.4Z");
}

</style>
