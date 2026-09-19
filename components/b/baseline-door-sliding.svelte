<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w969ec-iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-door-sliding" {...props}></Icon>
<style>
:global(.w969ec-iy) {
  fill: currentColor;
  d: path("M20 19V5c0-1.1-.9-2-2-2h-5.25v16h-1.5V3H6c-1.1 0-2 .9-2 2v14H3v2h18v-2zm-10-6H8v-2h2zm6 0h-2v-2h2z");
}

</style>
