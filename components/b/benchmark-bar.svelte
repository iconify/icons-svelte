<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="owuauzbqc"/><rect class="a0z7u_b4k"/><rect class="qych-cc0m"/><path class="tcj8xqrkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:benchmark-bar" {...props}></Icon>
<style>
:global(.a0z7u_b4k) {
  width: 4px;
  height: 11.5px;
  x: 10px;
  y: 9.25px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.owuauzbqc) {
  width: 4px;
  height: 7.5px;
  x: 3.25px;
  y: 13.25px;
  rx: 1.25px;
}

:global(.qych-cc0m) {
  width: 4px;
  height: 9px;
  x: 16.75px;
  y: 11.75px;
  rx: 1.25px;
}

:global(.tcj8xqrkg) {
  d: path("M2.75 5.25h2.5m2.85 0h2.5m2.8 0h2.5m2.85 0h2.5");
}

</style>
