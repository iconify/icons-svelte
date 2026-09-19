<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="tl1mwm89a"/><path class="jhmq-bc0k"/><circle class="alk8ko5pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-findmyphone" {...props}></Icon>
<style>
:global(.alk8ko5pa) {
  cx: 24px;
  cy: 35px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jhmq-bc0k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 12h9");
}

:global(.tl1mwm89a) {
  width: 27.186px;
  height: 37px;
  x: 10.407px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
}

</style>
