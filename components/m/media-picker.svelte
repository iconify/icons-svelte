<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s82ze2b_w"/><rect class="j77_a09ps"/><path class="lg817jbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:media-picker" {...props}></Icon>
<style>
:global(.j77_a09ps) {
  width: 28.788px;
  height: 28.788px;
  x: 13.712px;
  y: 5.549px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.112px;
  ry: 3.112px;
}

:global(.lg817jbmk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.684 28.215h20.54l-7.072-8.923l-4.63 5.935l-3.24-3.746z");
}

:global(.s82ze2b_w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.757 42.45H10.26a4.75 4.75 0 0 1-4.76-4.758V12.235");
}

</style>
