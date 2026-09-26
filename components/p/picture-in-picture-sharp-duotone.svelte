<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ose1lsbtw"/><path class="hfu1j8bzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:picture-in-picture-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hfu1j8bzf) {
  d: path("M22 9L22 4L2 4L2 20L9 20");
}

:global(.ose1lsbtw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 11L22 11C22.5523 11 23 11.4477 23 12L23 20C23 20.5523 22.5523 21 22 21L12 21C11.4477 21 11 20.5523 11 20L11 12C11 11.4477 11.4477 11 12 11Z");
  stroke: none;
}

</style>
