<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r_z0iplrz"/><path class="qe9ouvbgc"/><path class="g61xwsb1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:assist" {...props}></Icon>
<style>
:global(.g61xwsb1d) {
  d: path("m17 6.5l3.5.5l.5-3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qe9ouvbgc) {
  d: path("M4.25 10.5q4 4.5 0 9m9.5-9q-4 4.5 0 9M9 5.5q6-6 11.5 1.5");
}

:global(.r_z0iplrz) {
  d: path("M2.5 15a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0M9 8.5v13M2.5 15h13");
}

</style>
