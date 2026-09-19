<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="i5rwi4sts"/><path class="ekup168ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:key" {...props}></Icon>
<style>
:global(.ekup168ny) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 32.55V24h0h-21.91m16.3 4.93V24");
}

:global(.i5rwi4sts) {
  cx: 13.05px;
  cy: 24px;
  r: 8.55px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
