<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sthl-zbwj"/><path class="i457yabmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gorzdrav" {...props}></Icon>
<style>
:global(.i457yabmo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.6 36.8L31.4 24L18.6 11.197v7.4H7.5V29.4h11.1z");
}

:global(.sthl-zbwj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.6 5.5v11.1H5.5v14.8h11.1v11.1h14.8V31.4h11.1V16.6H31.4V5.5z");
}

</style>
