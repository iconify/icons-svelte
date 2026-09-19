<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aszgusblo"/><path class="o1_-ibc6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:powerapp" {...props}></Icon>
<style>
:global(.aszgusblo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.86 12a15.51 15.51 0 1 1-19.77.05L9.83 7.83a21.5 21.5 0 1 0 28.34 0Z");
}

:global(.o1_-ibc6k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.1 2.5h5.8V24h-5.8z");
}

</style>
