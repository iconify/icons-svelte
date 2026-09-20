<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="leg5z9b9q"/><path class="oviggobsx"/><path class="hsbaytb4s"/><path class="ybyc8pxiv"/><path class="kkm03rbxe"/><path class="gdxs68qsm"/><path class="utps5obsq"/><path class="axphtybjp"/><path class="r1wy_ibgj"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coral-reef-duotone-bold" {...props}></Icon>
<style>
:global(.axphtybjp) {
  d: path("M15 21V9l-3 -3");
}

:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.gdxs68qsm) {
  d: path("M7 21v-9L4 9");
}

:global(.hsbaytb4s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 21V9l-3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kkm03rbxe) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.leg5z9b9q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 21v-9L4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oviggobsx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1wy_ibgj) {
  d: path("m15 13 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.utps5obsq) {
  d: path("m7 15 4 -4");
}

:global(.ybyc8pxiv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 13 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
