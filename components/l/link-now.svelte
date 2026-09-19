<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="szo2qp1eh"/><path class="l8kz7pbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:link-now" {...props}></Icon>
<style>
:global(.l8kz7pbhe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.66 24.895c5.012 6.722 15.075 6.768 20.683 0");
}

:global(.szo2qp1eh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.924 9.174H32.66c15.436 0 15.015 28.994-5.327 29.653v-3.67H16.225c-16.39 0-14.762-25.983-.301-25.983");
}

</style>
