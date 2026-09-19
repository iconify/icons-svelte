<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gzcz85ryy"/><g class="y9tr6bcfx"><rect class="w5ztvbg7m"/><path class="w9v12qzbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-simple-10" {...props}></Icon>
<style>
:global(.gzcz85ryy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.251 30.667c0 2.963 2.37 5.333 5.334 5.333s5.135-2.37 5.135-5.333v-5.334c0-2.963-2.37-5.333-5.135-5.333s-5.334 2.37-5.334 5.333zM13.28 22.2l4-2.2m0 0v16");
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
