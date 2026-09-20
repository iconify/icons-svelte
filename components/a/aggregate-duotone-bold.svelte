<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sp3vxcbrc"/><path class="sf_49krow"/><path class="ahtjqxbfc"/><path class="y1s8ocbep"/><path class="io5188b_g"/><path class="s9xdwbcyw"/><path class="pesxdybze"/><path class="nkayykbew"/><path class="b603-acaz"/><path class="adiugjbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aggregate-duotone-bold" {...props}></Icon>
<style>
:global(.adiugjbhs) {
  d: path("m15 9 3 3 -3 3");
}

:global(.ahtjqxbfc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 19 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b603-acaz) {
  d: path("M10 12h8");
}

:global(.io5188b_g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nkayykbew) {
  d: path("m3 19 7 -7");
}

:global(.pesxdybze) {
  d: path("M3 12h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s9xdwbcyw) {
  d: path("m3 5 7 7");
}

:global(.sf_49krow) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sp3vxcbrc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 5 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y1s8ocbep) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
