<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b2b6babct"/><path class="pp--out0p"/><path class="ojb_ipbvm"/><path class="l5p5yybyx"/><path class="enu8lyb0i"/><path class="ewmg6nb_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cascade-duotone-thin" {...props}></Icon>
<style>
:global(.b2b6babct) {
  fill: currentColor;
  d: path("M5 2.5 7.5 5 5 7.5 2.5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.enu8lyb0i) {
  d: path("m12 9.5 2.5 2.5 -2.5 2.5L9.5 12Z");
}

:global(.ewmg6nb_g) {
  d: path("m19 16.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l5p5yybyx) {
  d: path("M5 2.5 7.5 5 5 7.5 2.5 5Z");
}

:global(.ojb_ipbvm) {
  fill: currentColor;
  d: path("m19 16.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pp--out0p) {
  fill: currentColor;
  d: path("m12 9.5 2.5 2.5 -2.5 2.5L9.5 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
