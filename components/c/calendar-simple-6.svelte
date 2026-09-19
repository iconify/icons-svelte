<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="x5hwmfx5f"/><path class="m4wtvmses"/></g><g class="y9tr6bcfx"><rect class="w5ztvbg7m"/><path class="w9v12qzbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-simple-6" {...props}></Icon>
<style>
:global(.m4wtvmses) {
  d: path("M28.74 21.975C27.95 20.79 26.569 20 24.396 20H24a5.31 5.31 0 0 0-5.333 5.333v5.334");
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

:global(.x5hwmfx5f) {
  cx: 24px;
  cy: 30.667px;
  r: 5.333px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
