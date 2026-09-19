<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="m1wsugg0s"/><rect class="pie97lbdx"/><rect class="d1d53-tuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cuberun" {...props}></Icon>
<style>
:global(.d1d53-tuq) {
  width: 6.093px;
  height: 6.088px;
  x: 33.407px;
  y: 9.711px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.387px;
  ry: 1.387px;
}

:global(.m1wsugg0s) {
  width: 14.846px;
  height: 14.846px;
  x: 17.02px;
  y: 23.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.003px;
  ry: 2.003px;
}

:global(.pie97lbdx) {
  width: 7.703px;
  height: 7.703px;
  x: 8.5px;
  y: 12.394px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.541px;
  ry: 1.541px;
}

</style>
