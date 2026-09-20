<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jof7c9fpk"/><path class="a6o5bdc8o"/><path class="m-p3hbclp"/><path class="z8bw_gbrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-right-left-outline-thin" {...props}></Icon>
<style>
:global(.a6o5bdc8o) {
  d: path("m16 5 4 4 -4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jof7c9fpk) {
  d: path("M4 9h16");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.z8bw_gbrq) {
  d: path("m8 11 -4 4 4 4");
}

</style>
