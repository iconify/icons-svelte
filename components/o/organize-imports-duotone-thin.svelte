<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgo4r57ki"/><path class="fx-2c_44o"/><path class="k5nkjp5cz"/><path class="c-w5_ulpy"/><path class="suz0t0a-u"/><path class="n_h_kpigg"/><path class="jkka-vwvt"/><path class="a6mnjib5x"/><path class="f9457j_px"/><path class="hzn91qbfm"/><path class="w2atjyb_m"/><path class="g_k4zfu5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:organize-imports-duotone-thin" {...props}></Icon>
<style>
:global(.a6mnjib5x) {
  d: path("M3 10h4");
}

:global(.c-w5_ulpy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f9457j_px) {
  d: path("M3 15h7");
}

:global(.fx-2c_44o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g_k4zfu5d) {
  d: path("M14 15h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzn91qbfm) {
  d: path("M14 5h6");
}

:global(.jkka-vwvt) {
  d: path("M3 5h6");
}

:global(.k5nkjp5cz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgo4r57ki) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n_h_kpigg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.suz0t0a-u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w2atjyb_m) {
  d: path("M14 10h6");
}

</style>
