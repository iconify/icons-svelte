<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j5gtq7b4i"/><path class="m9uuv3bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:auphonic-edit" {...props}></Icon>
<style>
:global(.j5gtq7b4i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 33.75c0-10.77-8.73-19.5-19.5-19.5S4.5 22.98 4.5 33.75");
}

:global(.m9uuv3bbr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 33.75c0-7.456-6.044-13.5-13.5-13.5s-13.5 6.044-13.5 13.5");
}

</style>
