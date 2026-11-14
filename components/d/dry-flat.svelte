<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dm8932bfa"/><path class="g2dxp65no"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dry-flat" {...props}></Icon>
<style>
:global(.dm8932bfa) {
  d: path("M7 5.5h10A3.5 3.5 0 0 1 20.5 9v2.5A3.5 3.5 0 0 1 17 15H7a3.5 3.5 0 0 1-3.5-3.5V9A3.5 3.5 0 0 1 7 5.5m-4.5 13h19");
}

:global(.g2dxp65no) {
  d: path("m9 5.5l3 3.25l3-3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
