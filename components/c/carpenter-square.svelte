<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sg4kogbvy"/><rect class="cyippmbuc"/><path class="s5fv-sc4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:carpenter-square" {...props}></Icon>
<style>
:global(.cyippmbuc) {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 17.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s5fv-sc4e) {
  d: path("M10 17.25V19m3.5-1.75V19m3.5-1.75V19");
}

:global(.sg4kogbvy) {
  width: 4px;
  height: 14.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1px;
}

</style>
