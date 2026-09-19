<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ijdhsmbpl"/><g class="y9tr6bcfx"><rect class="w5ztvbg7m"/><path class="w9v12qzbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-simple-7" {...props}></Icon>
<style>
:global(.ijdhsmbpl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.7 36l8.6-16H18.7");
}

:global(.w5ztvbg7m) {
  width: 35px;
  height: 36px;
  x: 6.5px;
  y: 7.5px;
  rx: 4px;
  ry: 4px;
}

:global(.w9v12qzbx) {
  d: path("M33.5 4.5v6m-19-6v6");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
