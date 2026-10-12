<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="efs8xfsoz"/><circle class="wmzeeu32g"/><circle class="o19ergbhs"/><circle class="pftf-cbrq"/><circle class="i87l21lle"/><circle class="hft84rbnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-dot-plot" {...props}></Icon>
<style>
:global(.efs8xfsoz) {
  cx: 4.75px;
  cy: 18px;
  r: 1.75px;
}

:global(.hft84rbnc) {
  cx: 19.25px;
  cy: 18px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i87l21lle) {
  cx: 19.25px;
  cy: 12.25px;
  r: 1.75px;
}

:global(.o19ergbhs) {
  cx: 12px;
  cy: 12.25px;
  r: 1.75px;
}

:global(.pftf-cbrq) {
  cx: 12px;
  cy: 6.5px;
  r: 1.75px;
}

:global(.wmzeeu32g) {
  cx: 12px;
  cy: 18px;
  r: 1.75px;
}

</style>
