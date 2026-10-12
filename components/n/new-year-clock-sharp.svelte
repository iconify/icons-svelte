<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="a_3y1e_gc"/><path class="cueqsyb3v"/><path class="tq0y9obbf"/><path class="camndabwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:new-year-clock-sharp" {...props}></Icon>
<style>
:global(.a_3y1e_gc) {
  cx: 11.5px;
  cy: 13.75px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.camndabwv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.31 7.28l2.13 1.79l.46.38l.21-.56l1.93-5.08l.21-.56l-.5.34l-4.4 2.97l-.5.34z");
}

:global(.cueqsyb3v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 13.75v-5m0 5V10");
}

:global(.tq0y9obbf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 13.75h.01m-5.01 5h.01m-5.01-5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
