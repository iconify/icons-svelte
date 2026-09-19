<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ex4iombak"/><path class="hquj44b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:anythingtopip" {...props}></Icon>
<style>
:global(.ex4iombak) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.601 30.483a82.5 82.5 0 0 1-11.238-.86a75.5 75.5 0 0 1 0-23.147a75.4 75.4 0 0 1 23.145 0a63.4 63.4 0 0 1 .861 10.775");
}

:global(.hquj44b2e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.637 41.524a75.4 75.4 0 0 1-23.145 0a75.5 75.5 0 0 1 0-23.146a75.4 75.4 0 0 1 23.145 0a75.5 75.5 0 0 1 0 23.146");
}

</style>
