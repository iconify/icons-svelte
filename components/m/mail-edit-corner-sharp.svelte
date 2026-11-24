<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4f5adbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-edit-corner-sharp" {...props}></Icon>
<style>
:global(.s4f5adbdp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 19H3V5h18v6M3 5l6 6h6l6-6m-7 16v-3l4-4l3 3l-4 4Z");
}

</style>
