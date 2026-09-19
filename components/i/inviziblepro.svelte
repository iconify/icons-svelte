<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="zs0thy8vn"/><path class="o6_xijhdh"/><circle class="u4ldjccli"/><circle class="k60_wee2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:inviziblepro" {...props}></Icon>
<style>
:global(.k60_wee2u) {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
}

:global(.o6_xijhdh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M40 40L8 8");
}

:global(.u4ldjccli) {
  cx: 24px;
  cy: 24px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
}

:global(.zs0thy8vn) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  rx: 19.5px;
  ry: 12.01px;
}

</style>
