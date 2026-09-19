<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qwxm6qfek"/><path class="jynvynjqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:82-nagano-bank" {...props}></Icon>
<style>
:global(.jynvynjqj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 40.024L24 29.342l6.166 10.682l6.167-10.682M24 18.659l9.25 16.024");
}

:global(.qwxm6qfek) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 40.024L24 7.977l18.5 32.047zm6.167 0l15.417-26.706");
}

</style>
