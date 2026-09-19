<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wui1logvc"/><circle class="bfm5ob_ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:resurs" {...props}></Icon>
<style>
:global(.bfm5ob_ma) {
  cx: 24px;
  cy: 24px;
  r: 11.556px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wui1logvc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.556 24c0 8.576-6.952 15.528-15.528 15.528S4.5 32.576 4.5 24zm-23.112 0c0-8.576 6.952-15.528 15.528-15.528S43.5 15.424 43.5 24z");
}

</style>
