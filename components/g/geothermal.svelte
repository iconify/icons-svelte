<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oz683kbwp"/><circle class="ts6ik8buj"/><path class="ymd_5iu5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:geothermal" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oz683kbwp) {
  width: 18.5px;
  height: 8.75px;
  x: 2.75px;
  y: 12.5px;
  rx: 2.5px;
}

:global(.ts6ik8buj) {
  cx: 12px;
  cy: 16.875px;
  r: 2px;
}

:global(.ymd_5iu5a) {
  d: path("M8 9.5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5");
}

</style>
