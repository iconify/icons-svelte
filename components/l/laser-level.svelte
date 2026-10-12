<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rz6ve3-4p"/><path class="nrww_8b9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:laser-level" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nrww_8b9h) {
  d: path("M7 8.75h3M8.5 12.5V17M5 20.25L8.5 17l3.5 3.25m3.25-11.5h2.25m2 0h1.75");
}

:global(.rz6ve3-4p) {
  width: 10px;
  height: 7.5px;
  x: 3.5px;
  y: 5px;
  rx: 2px;
}

</style>
