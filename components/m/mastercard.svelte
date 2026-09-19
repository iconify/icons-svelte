<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="emh3m8rlv"/><circle class="bbg0zb9fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mastercard" {...props}></Icon>
<style>
:global(.bbg0zb9fi) {
  cx: 32.1px;
  cy: 24px;
  r: 12.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.emh3m8rlv) {
  cx: 15.9px;
  cy: 24px;
  r: 12.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
