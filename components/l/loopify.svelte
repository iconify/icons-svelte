<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="jwlr4_bnu"/><circle class="uw-gybb6f"/><circle class="o7opl6brf"/><circle class="vq-r8upje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:loopify" {...props}></Icon>
<style>
:global(.jwlr4_bnu) {
  cx: 14px;
  cy: 14.25px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.o7opl6brf) {
  cx: 14px;
  cy: 33.75px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.uw-gybb6f) {
  cx: 34px;
  cy: 14.25px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vq-r8upje) {
  cx: 34px;
  cy: 33.75px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
