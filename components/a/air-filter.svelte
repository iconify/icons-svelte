<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="soqifdb1n"/><path class="qbq7igoku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:air-filter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qbq7igoku) {
  d: path("m5.25 8.5l2.25 7l2.25-7l2.25 7l2.25-7l2.25 7l2.25-7");
}

:global(.soqifdb1n) {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 5.5px;
  rx: 2px;
}

</style>
