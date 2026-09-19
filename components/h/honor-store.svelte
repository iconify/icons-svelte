<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="u1a0m2bhs"/><path class="pg2z1bbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:honor-store" {...props}></Icon>
<style>
:global(.pg2z1bbvw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 13.5a8 8 0 1 1 16 0M20.626 24v8m6.748-8v8m-6.748-4.015h6.748");
}

:global(.u1a0m2bhs) {
  width: 37px;
  height: 29px;
  x: 5.5px;
  y: 13.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
