<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aa4-lvb4b"/><path class="s2my15a3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pixelix" {...props}></Icon>
<style>
:global(.aa4-lvb4b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.375 33.75h9.75v9.75h-9.75zm9.75-19.5h19.5v19.5h-19.5z");
}

:global(.s2my15a3y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.375 4.5h19.5V24h-19.5z");
}

</style>
