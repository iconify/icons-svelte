<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ej8lcn6yp"/><circle class="oqa9v-w7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:moonpay" {...props}></Icon>
<style>
:global(.ej8lcn6yp) {
  cx: 19.5px;
  cy: 28.5px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.oqa9v-w7b) {
  cx: 37px;
  cy: 11px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
