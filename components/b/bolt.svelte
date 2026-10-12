<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z_fh47b7m"/><rect class="cpq7qdbcw"/><path class="p26vdgvbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bolt" {...props}></Icon>
<style>
:global(.cpq7qdbcw) {
  width: 5px;
  height: 13.5px;
  x: 9.5px;
  y: 7.75px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p26vdgvbg) {
  d: path("M10.25 2.75v5m3.5-5v5m-4.25 4.5l5-1.25m-5 4.75l5-1.25m-5 4.75l5-1.25");
}

:global(.z_fh47b7m) {
  width: 12px;
  height: 5px;
  x: 6px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
