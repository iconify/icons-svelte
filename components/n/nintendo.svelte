<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="f7r02vbbo"/><path class="aj9nz6roq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nintendo" {...props}></Icon>
<style>
:global(.aj9nz6roq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.642 30.499V17.501L29.358 30.5v-13");
}

:global(.f7r02vbbo) {
  width: 39px;
  height: 27px;
  x: 4.5px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.5px;
  ry: 13.5px;
}

</style>
