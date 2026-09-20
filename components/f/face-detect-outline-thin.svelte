<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mp8d-bcnh"/><path class="dyzdq66vg"/><path class="a75-p3jrr"/><path class="gllvw82zq"/><path class="i4lcqvyfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:face-detect-outline-thin" {...props}></Icon>
<style>
:global(.a75-p3jrr) {
  d: path("M13.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.dyzdq66vg) {
  d: path("M8.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gllvw82zq) {
  d: path("M3 7V3h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4lcqvyfj) {
  d: path("M21 17v4h-4");
}

:global(.mp8d-bcnh) {
  d: path("M5 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

</style>
