<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="gwpkjccoj"/><path class="ptzg8vaxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:intra" {...props}></Icon>
<style>
:global(.gwpkjccoj) {
  cx: 24px;
  cy: 19.218px;
  r: 10.561px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ptzg8vaxz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 39.343l19.5-19.5l19.5 19.5z");
}

</style>
