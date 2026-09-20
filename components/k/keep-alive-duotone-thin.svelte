<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="cc0pq4b_o"/><path class="jja8o5fel"/><path class="hu9l57rhm"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="vslz5yb3q"/><path class="cvahx_bgf"/><path class="ji1cfccfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keep-alive-duotone-thin" {...props}></Icon>
<style>
:global(.cc0pq4b_o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cvahx_bgf) {
  d: path("m9 9 3 -3 3 3");
}

:global(.fcstqn4mf) {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hu9l57rhm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ji1cfccfb) {
  d: path("m9 15 3 3 3 -3");
}

:global(.jja8o5fel) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 9 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ph8xawbhr) {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rsea1pbos) {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.zuquf0b8s) {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
