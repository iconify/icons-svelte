<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="rz-vvzbbj"/><path class="v8g8mjb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nocria" {...props}></Icon>
<style>
:global(.rz-vvzbbj) {
  width: 39px;
  height: 14px;
  x: 4.5px;
  y: 17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

:global(.v8g8mjb4p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 31v-4h-31v4");
}

</style>
