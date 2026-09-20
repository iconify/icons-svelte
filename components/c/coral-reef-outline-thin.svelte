<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gdxs68qsm"/><path class="utps5obsq"/><path class="axphtybjp"/><path class="r1wy_ibgj"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coral-reef-outline-thin" {...props}></Icon>
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

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r1wy_ibgj) {
  d: path("m15 13 4 -4");
}

:global(.utps5obsq) {
  d: path("m7 15 4 -4");
}

</style>
