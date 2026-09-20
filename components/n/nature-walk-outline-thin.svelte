<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zw_n0_vwa"/><path class="fe670vbuv"/><path class="fmlaifbpn"/><path class="l5q9_cc7w"/><path class="t630gdbxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nature-walk-outline-thin" {...props}></Icon>
<style>
:global(.fe670vbuv) {
  d: path("m12 8 8 8H4Z");
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

:global(.l5q9_cc7w) {
  d: path("M2 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.t630gdbxd) {
  d: path("M7 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zw_n0_vwa) {
  d: path("m12 3 7 7H5Z");
}

</style>
