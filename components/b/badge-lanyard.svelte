<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="eht8p590i"/><path class="hmlvhtb4p"/><circle class="s2ny7rbmr"/><path class="dl_vrzbhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:badge-lanyard" {...props}></Icon>
<style>
:global(.dl_vrzbhu) {
  d: path("M8.5 17.75c.6-1.5 2-2.5 3.5-2.5s2.9 1 3.5 2.5");
}

:global(.eht8p590i) {
  width: 14.5px;
  height: 17.5px;
  x: 4.75px;
  y: 3.75px;
  rx: 2.5px;
}

:global(.hmlvhtb4p) {
  d: path("M10 6.5h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s2ny7rbmr) {
  cx: 12px;
  cy: 11.5px;
  r: 2.25px;
}

</style>
