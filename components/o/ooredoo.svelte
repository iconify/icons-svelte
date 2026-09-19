<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ej8lcn6yp"/><circle class="owolpfbxm"/><circle class="u7ye2infl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ooredoo" {...props}></Icon>
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

:global(.owolpfbxm) {
  cx: 19.5px;
  cy: 28.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u7ye2infl) {
  cx: 38px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
