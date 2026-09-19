<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vpvm13bbr"/><circle class="ylmcyr_jq"/><circle class="nrcmzcb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pacman" {...props}></Icon>
<style>
:global(.nrcmzcb9s) {
  cx: 43.749px;
  cy: 24px;
  r: 1.751px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vpvm13bbr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 24l19.93-8.052h0a21.494 21.494 0 1 0-.144 16.45Z");
}

:global(.ylmcyr_jq) {
  cx: 37.247px;
  cy: 24px;
  r: 1.751px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
