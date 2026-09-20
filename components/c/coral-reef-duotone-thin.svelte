<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l45mc7cap"/><path class="aut5o13zt"/><path class="m2jk0x1pg"/><path class="f9mh2ubcr"/><path class="ymhw07_9a"/><path class="gdxs68qsm"/><path class="utps5obsq"/><path class="axphtybjp"/><path class="r1wy_ibgj"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coral-reef-duotone-thin" {...props}></Icon>
<style>
:global(.aut5o13zt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.axphtybjp) {
  d: path("M15 21V9l-3 -3");
}

:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.f9mh2ubcr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 13 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gdxs68qsm) {
  d: path("M7 21v-9L4 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l45mc7cap) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 21v-9L4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m2jk0x1pg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 21V9l-3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1wy_ibgj) {
  d: path("m15 13 4 -4");
}

:global(.utps5obsq) {
  d: path("m7 15 4 -4");
}

:global(.ymhw07_9a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
