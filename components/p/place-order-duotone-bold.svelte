<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z6qs6gbnt"/><path class="fmbgtccaf"/><path class="q12h31yct"/><path class="b-wj2gbav"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="c4khiwgvb"/><path class="gi1v2vyju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:place-order-duotone-bold" {...props}></Icon>
<style>
:global(.b-wj2gbav) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 12.5 16 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.fmbgtccaf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gi1v2vyju) {
  d: path("M13.5 12.5 16 15l-2.5 2.5");
}

:global(.q12h31yct) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tp7101bon) {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

:global(.yb0d-pkkp) {
  d: path("M4 8v14h16V8");
}

:global(.z6qs6gbnt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
