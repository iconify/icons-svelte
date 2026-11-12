<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ll_t976_m"/><path class="bp9f0acyy"/><path class="i1rjgtlrr"/><path class="hrpb3z6mg"/><path class="meafjacfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-collapse-minimalistic-line-duotone" {...props}></Icon>
<style>
:global(.bp9f0acyy) {
  d: path("M20 11L12 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.hrpb3z6mg) {
  stroke-linejoin: round;
  d: path("M5.28571 16L7 14L5.28571 12");
}

:global(.i1rjgtlrr) {
  d: path("M20 6L12 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ll_t976_m) {
  d: path("M20 16H12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.meafjacfv) {
  stroke-linejoin: round;
  d: path("M5.28571 10L7 8L5.28571 6");
}

</style>
