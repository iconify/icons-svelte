<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg3yf36oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:location-automation-outline" {...props}></Icon>
<style>
:global(.wg3yf36oh) {
  fill: currentColor;
  d: path("M4 19V7l8-6l8 6v4h-2V8l-6-4.5L6 8v9h6v2H4Zm8-8.75ZM18.5 22l-1.4-3.1l-3.1-1.4l3.1-1.4l1.4-3.1l1.4 3.1l3.1 1.4l-3.1 1.4l-1.4 3.1Z");
}

</style>
