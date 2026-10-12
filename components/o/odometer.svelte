<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ppkmu3b3c"/><rect class="an3bdealf"/><path class="nxv4f3b5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:odometer" {...props}></Icon>
<style>
:global(.an3bdealf) {
  width: 13.5px;
  height: 4.25px;
  x: 5.25px;
  y: 9.5px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nxv4f3b5b) {
  d: path("M8.63 9.5v4.25M12 9.5v4.25m3.38-4.25v4.25");
}

:global(.ppkmu3b3c) {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 7px;
  rx: 2.5px;
}

</style>
