<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w1wi7obvc"/><path class="vyrk3096t"/><path class="pm30vmtce"/><path class="xr2rcq_ip"/><path class="qtxvlht3c"/><path class="vc2-n5bxy"/><path class="w_nev909g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:matchmaking-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pm30vmtce) {
  d: path("M2 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

:global(.vc2-n5bxy) {
  d: path("m11 14 -3 3 3 3");
}

:global(.vyrk3096t) {
  fill: currentColor;
  d: path("M14 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w_nev909g) {
  d: path("m13 14 3 3 -3 3");
}

:global(.w1wi7obvc) {
  fill: currentColor;
  d: path("M2 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xr2rcq_ip) {
  d: path("M14 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
