<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uvlwxgw4w"/><path class="g62o_vk5q"/><path class="emw_5qbdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:curtains-sharp-duotone" {...props}></Icon>
<style>
:global(.emw_5qbdm) {
  d: path("M2 3H22M8 3V10M16 3V10");
}

:global(.g62o_vk5q) {
  fill: currentColor;
  d: path("M13 22H11V3H13V22Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uvlwxgw4w) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 4H21V21C21 21.552 20.552 22 20 22H4C3.448 22 3 21.552 3 21V4H2V2H22V4Z");
  stroke: none;
}

</style>
