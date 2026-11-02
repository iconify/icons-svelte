<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgbug4bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plug-fill-round" {...props}></Icon>
<style>
:global(.wgbug4bwy) {
  fill: currentColor;
  d: path("M10 6h4V3a1 1 0 0 1 2 0v3.416A5 5 0 0 1 19 11v2a5 5 0 0 1-5 5h-1v3a1 1 0 0 1-2 0v-3h-1a5 5 0 0 1-5-5v-2c0-1.99 1.175-3.79 3-4.584V3a1 1 0 0 1 2 0Z");
}

</style>
