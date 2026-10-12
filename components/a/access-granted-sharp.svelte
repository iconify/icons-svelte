<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sbz0un9qe"/><path class="u5add9sjx"/><circle class="b6sj3-bad"/><path class="b4latebtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:access-granted-sharp" {...props}></Icon>
<style>
:global(.b4latebtc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.75 16.75l1.5 1.5l2.75-3");
}

:global(.b6sj3-bad) {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sbz0un9qe) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h11v18.5h-11z");
}

:global(.u5add9sjx) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.25 11.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
