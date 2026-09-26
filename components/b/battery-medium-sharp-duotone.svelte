<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hqygwwb5d"/><path class="c7rtlk8-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:battery-medium-sharp-duotone" {...props}></Icon>
<style>
:global(.c7rtlk8-m) {
  d: path("M22 8.5L22 15.5M6 9L6 15M10 9L10 15");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hqygwwb5d) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5L18 5C18.5523 5 19 5.4477 19 6L19 18C19 18.5523 18.5523 19 18 19L2 19C1.4477 19 1 18.5523 1 18L1 6C1 5.4477 1.4477 5 2 5Z");
  stroke: none;
}

</style>
