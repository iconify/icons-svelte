<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6q7r5bds"/><path class="krwm4ebpd"/><path class="i-p6cdb1m"/><path class="zgii3-qwi"/><path class="i_p7ghz-x"/><path class="x02q_d2hh"/><path class="bbuvl1-kv"/><path class="hr8tx7nsp"/><path class="ew7y79byi"/><path class="huj3g_bus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:baby-shower-duotone-thin" {...props}></Icon>
<style>
:global(.bbuvl1-kv) {
  d: path("M4 13h14");
}

:global(.ew7y79byi) {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f6q7r5bds) {
  fill: currentColor;
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hr8tx7nsp) {
  d: path("m18 13 3 -3");
}

:global(.huj3g_bus) {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.i_p7ghz-x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 13 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i-p6cdb1m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 13a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.krwm4ebpd) {
  fill: currentColor;
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x02q_d2hh) {
  d: path("M4 13a7 7 0 0 1 14 0");
}

:global(.zgii3-qwi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
