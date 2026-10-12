<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dx-zi1ltd"/><path class="u83ecs0hu"/><circle class="hzma9bb3u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:caravan" {...props}></Icon>
<style>
:global(.dx-zi1ltd) {
  width: 15px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzma9bb3u) {
  cx: 8px;
  cy: 18.25px;
  r: 2.5px;
}

:global(.u83ecs0hu) {
  d: path("M5.75 8.75h4.5v3.5h-4.5Zm7 9.5V10H15v8.25m2.75-2h3.5");
}

</style>
