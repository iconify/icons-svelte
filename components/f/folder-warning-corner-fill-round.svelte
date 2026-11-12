<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3zbsvbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-warning-corner-fill-round" {...props}></Icon>
<style>
:global(.l3zbsvbkl) {
  fill: currentColor;
  d: path("M10.707 3.293L12.414 5H19a3 3 0 0 1 3 3a1 1 0 0 1-1 1h-9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293M18 18a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm-1 2h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
