<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ip54ocb4w"/><path class="lcsfzhb6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paper-plane-clock-corner-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ip54ocb4w) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11.684 2.051a1.001 1.001 0 0 1 1.265 1.265l-3 9a1 1 0 0 1-1.843.131L6.255 8.745L2.553 6.894a1 1 0 0 1 .131-1.843Z");
}

:global(.lcsfzhb6y) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4L3 6l4 2l2 4l3-9zM7 8l1-1m4 10a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
