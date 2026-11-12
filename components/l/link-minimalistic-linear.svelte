<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="arzno-wyz"/><path class="xk1mui9dn"/><path class="tgsr-hz9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-minimalistic-linear" {...props}></Icon>
<style>
:global(.arzno-wyz) {
  d: path("M8.99991 11.9999H14.9999");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tgsr-hz9s) {
  d: path("M15 6H16C19.3137 6 22 8.68629 22 12C22 15.3137 19.3137 18 16 18H15");
}

:global(.xk1mui9dn) {
  d: path("M9 18H8C4.68629 18 2 15.3137 2 12C2 8.68629 4.68629 6 8 6H9");
}

</style>
