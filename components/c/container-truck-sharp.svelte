<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ulxnfkqvr"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="r6parkbau"/><path class="t66ctv5hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:container-truck-sharp" {...props}></Icon>
<style>
:global(.ox2ue_b-w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

:global(.r_0b548wt) {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r6parkbau) {
  cx: 19px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t66ctv5hf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 19h.01");
}

:global(.ulxnfkqvr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5H14v10.25H2.75zm3 2.5v5m3-5v5m3-5v5m5-4.25v-1h2.705l.445.67l1.1 1.6l.25.368v5.362h-4.5Zm0 2.5h4.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
