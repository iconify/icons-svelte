<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="vv2x70_ud"/><rect class="i3wjx5b6h"/><circle class="f2u3p_sgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:io" {...props}></Icon>
<style>
:global(.f2u3p_sgi) {
  cx: 7.78px;
  cy: 11.922px;
  r: 3.28px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i3wjx5b6h) {
  width: 6.561px;
  height: 20.047px;
  x: 4.5px;
  y: 19.311px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.28px;
}

:global(.vv2x70_ud) {
  cx: 30.597px;
  cy: 26.455px;
  r: 12.903px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
