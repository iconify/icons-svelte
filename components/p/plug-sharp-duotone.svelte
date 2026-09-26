<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="emhh_6bfz"/><path class="uvsqb_-sh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plug-sharp-duotone" {...props}></Icon>
<style>
:global(.emhh_6bfz) {
  stroke-opacity: 0.4;
  d: path("M9 1L9 7M15 1L15 7M12 18L12 23");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uvsqb_-sh) {
  fill: currentColor;
  d: path("M5 6L19 6C19.5523 6 20 6.4477 20 7L20 11C20 15.2802 16.2802 19 12 19C7.7198 19 4 15.2802 4 11L4 7C4 6.4477 4.4477 6 5 6Z");
  stroke: none;
}

</style>
