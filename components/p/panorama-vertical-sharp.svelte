<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5zrrdl4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:panorama-vertical-sharp" {...props}></Icon>
<style>
:global(.o5zrrdl4b) {
  fill: currentColor;
  d: path("M3.475 21.95q.875-1.875 1.45-4.5t.575-5.5t-.575-5.5t-1.45-4.5H20.5q-.875 1.875-1.437 4.5t-.563 5.5t.563 5.5t1.437 4.5z");
}

</style>
