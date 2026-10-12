<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rd454dc-j"/><rect class="b52yv8w1g"/><path class="hb_y1exot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:access-point-secure" {...props}></Icon>
<style>
:global(.b52yv8w1g) {
  width: 6px;
  height: 5px;
  x: 9px;
  y: 13.75px;
  rx: 1.25px;
}

:global(.hb_y1exot) {
  d: path("M10 13.75V12.5a2 2 0 0 1 4 0v1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rd454dc-j) {
  d: path("M2.92 7.25a12 12 0 0 1 18.16 0M7 9.5a7.5 7.5 0 0 1 10 0M5 21.25h14");
}

</style>
