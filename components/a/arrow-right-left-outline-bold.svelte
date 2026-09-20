<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jof7c9fpk"/><path class="a6o5bdc8o"/><path class="m-p3hbclp"/><path class="z8bw_gbrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-right-left-outline-bold" {...props}></Icon>
<style>
:global(.a6o5bdc8o) {
  d: path("m16 5 4 4 -4 4");
}

:global(.jof7c9fpk) {
  d: path("M4 9h16");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z8bw_gbrq) {
  d: path("m8 11 -4 4 4 4");
}

</style>
