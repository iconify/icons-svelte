<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lq2omjlsq"/><path class="uuw5qpber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:a9gag" {...props}></Icon>
<style>
:global(.lq2omjlsq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.93 14.25L24 24L7.07 14.25");
}

:global(.uuw5qpber) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.07 14.25L24 4.5l16.93 9.75v19.5L24 43.5L7.07 33.75");
}

</style>
