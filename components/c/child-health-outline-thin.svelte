<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_m3g48-w"/><path class="hy1q78bil"/><path class="m0_70pbcq"/><path class="k1llj9blt"/><path class="f2m4wubik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:child-health-outline-thin" {...props}></Icon>
<style>
:global(.f2m4wubik) {
  d: path("M13 12h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hy1q78bil) {
  d: path("M8 9v5");
}

:global(.k1llj9blt) {
  d: path("M17 8v8");
}

:global(.m0_70pbcq) {
  d: path("m4 19 5 -5 5 5");
}

:global(.t_m3g48-w) {
  d: path("M5 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
