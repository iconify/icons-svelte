<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yoou77b3v"/><path class="fd6v2-iry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monitor" {...props}></Icon>
<style>
:global(.fd6v2-iry) {
  d: path("M12 16.25v4m-3.75 0h7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yoou77b3v) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>
