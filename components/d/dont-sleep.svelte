<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="erd8-3b3h"/><rect class="wshc33b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dont-sleep" {...props}></Icon>
<style>
:global(.erd8-3b3h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.362 11.692h17.276v24.616H15.362z");
}

:global(.wshc33b9v) {
  width: 24.319px;
  height: 39px;
  x: 11.84px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.601px;
  ry: 3.601px;
}

</style>
