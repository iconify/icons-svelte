<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rbrrfcbln"/><path class="at_623xyx"/><path class="ys-dg812g"/><path class="jkuojibnm"/><path class="fmlaifbpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pallet-duotone-thin" {...props}></Icon>
<style>
:global(.at_623xyx) {
  d: path("M5 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.fmlaifbpn) {
  d: path("M12 16v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.rbrrfcbln) {
  fill: currentColor;
  d: path("M5 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
