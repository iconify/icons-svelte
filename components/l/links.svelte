<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="pfoiixbsg"/><circle class="r3d_mqsdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:links" {...props}></Icon>
<style>
:global(.pfoiixbsg) {
  cx: 17.745px;
  cy: 16.846px;
  r: 11.346px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r3d_mqsdg) {
  cx: 30.255px;
  cy: 31.154px;
  r: 11.346px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
