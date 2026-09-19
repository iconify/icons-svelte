<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nspz04b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:coverage-map" {...props}></Icon>
<style>
:global(.nspz04b7g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 8.373L5.5 11.592v28.035l12.333-3.219zm0 0l12.334 3.219v28.035l-12.334-3.219zm24.667 0l-12.333 3.219v28.035L42.5 36.408z");
}

</style>
