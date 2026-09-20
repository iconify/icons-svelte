<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eg1ir3b5p"/><path class="p5ke0gb-n"/><path class="hlzio5mhn"/><path class="vnfd-sbai"/><path class="mui_mi4_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:knitting-duotone-thin" {...props}></Icon>
<style>
:global(.eg1ir3b5p) {
  fill: currentColor;
  d: path("M3 15a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hlzio5mhn) {
  d: path("m13 12 8 -8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mui_mi4_l) {
  d: path("M5 13c3 2 5 4 6 7");
}

:global(.p5ke0gb-n) {
  d: path("M3 15a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.vnfd-sbai) {
  d: path("m16 15 5 -5");
}

</style>
