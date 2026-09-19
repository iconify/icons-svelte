<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="qqwfmrkwm"/><path class="h11y39b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:moneytracker" {...props}></Icon>
<style>
:global(.h11y39b7x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.135 31.36a5.48 5.48 0 0 0 4.6 2.07h2.76a4.6 4.6 0 0 0 0-9.2h-2.99a4.6 4.6 0 1 1 0-9.2h2.76c2.07 0 3.45.46 4.6 2.07m-5.98-4.6v23");
}

:global(.qqwfmrkwm) {
  cx: 24px;
  cy: 24px;
  r: 19.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
