<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w869ix7cy"/><path class="ibh1m8b4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cake-stand" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ibh1m8b4i) {
  d: path("M5.75 8.5h12.5m-15.5 4.75h18.5m-9.25 0v8m-3.75 0h7.5");
}

:global(.w869ix7cy) {
  width: 12.5px;
  height: 8px;
  x: 5.75px;
  y: 5.25px;
  rx: 2px;
}

</style>
