<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jfzhts04a"/><path class="dp1vl9bff"/><path class="cohh1bbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:daiso" {...props}></Icon>
<style>
:global(.cohh1bbau) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.123 42.5L24 28.965L37.877 42.5");
}

:global(.dp1vl9bff) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.123 31.108L24 17.573l13.877 13.535");
}

:global(.jfzhts04a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.123 19.035L24 5.5l13.877 13.535");
}

</style>
