<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g0ug28b6c"/><circle class="babe14szl"/><path class="yus9qngim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:blood-donor" {...props}></Icon>
<style>
:global(.babe14szl) {
  cx: 24px;
  cy: 35.983px;
  r: 7.517px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.g0ug28b6c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.347 29.352c-3.907-1.723-5.02-5.993-5.02-7.977c0-5.106 7.81-15.773 8.601-16.84c.035-.047.094-.047.129 0c.79 1.07 8.615 11.78 8.615 16.84c0 1.544-.953 6.163-4.893 7.977");
}

:global(.yus9qngim) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.448 35.915h9.104m-4.572 4.561v-9.104");
}

</style>
