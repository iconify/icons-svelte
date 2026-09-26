<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="j2zr0lb_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-spline-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.j2zr0lb_e) {
  d: path("M7 17C10.2098 16.3367 12.8536 14.0706 14 11C15.1464 7.9294 17.7902 5.6633 21 5");
}

:global(.p53xcyb3q) {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

</style>
