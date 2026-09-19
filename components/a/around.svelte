<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="dgke4cczh"/><circle class="nsnfffbjn"/><circle class="mm6ie8asn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:around" {...props}></Icon>
<style>
:global(.dgke4cczh) {
  cx: 24px;
  cy: 24px;
  r: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mm6ie8asn) {
  cx: 15.5px;
  cy: 24px;
  r: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nsnfffbjn) {
  cx: 32.5px;
  cy: 24px;
  r: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
