<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d9hsz4sou"/><path class="b2x5_60kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:home-plus" {...props}></Icon>
<style>
:global(.b2x5_60kp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 14.75h18.5a9.25 9.25 0 0 1 0 18.5h-18.5a9.25 9.25 0 0 1 0-18.5");
}

:global(.d9hsz4sou) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5za9.25 9.25 0 0 1 9.25 9.25v18.5a9.25 9.25 0 0 1-18.5 0v-18.5A9.25 9.25 0 0 1 24 5.5");
}

</style>
