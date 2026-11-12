<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l7y12ieah"/><path class="v8tx6ieir"/><path class="a-d731ccj"/><path class="hrpb3z6mg"/><path class="meafjacfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-collapse-minimalistic-linear" {...props}></Icon>
<style>
:global(.a-d731ccj) {
  d: path("M20 6L12 6");
}

:global(.hrpb3z6mg) {
  stroke-linejoin: round;
  d: path("M5.28571 16L7 14L5.28571 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l7y12ieah) {
  d: path("M20 16H12");
}

:global(.meafjacfv) {
  stroke-linejoin: round;
  d: path("M5.28571 10L7 8L5.28571 6");
}

:global(.v8tx6ieir) {
  d: path("M20 11L12 11");
}

</style>
