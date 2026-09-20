<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_3m1qbvo"/><path class="vktdccc-m"/><path class="pwougkblb"/><path class="ts7kflb8f"/><path class="yu-j7jb_g"/><path class="hwmj2eixw"/><path class="m0wo8tb6s"/><path class="ulyohmb5e"/><path class="u7sb4-hdn"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:counter-metric-duotone-thin" {...props}></Icon>
<style>
:global(.b_3m1qbvo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwmj2eixw) {
  d: path("M7 8.5v9");
}

:global(.m0wo8tb6s) {
  d: path("M4.5 9 7 6.5 9.5 9");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pwougkblb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 6.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ts7kflb8f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14.5 13 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u7sb4-hdn) {
  d: path("m14.5 13 2.5 2.5 2.5 -2.5");
}

:global(.ulyohmb5e) {
  d: path("M17 6.5v9");
}

:global(.vktdccc-m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9 7 6.5 9.5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
