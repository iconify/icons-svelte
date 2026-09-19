<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mz87j4bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bbc-weather" {...props}></Icon>
<style>
:global(.mz87j4bwm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.165h8.801V42.5H5.5zm18.666-9.864V5.5h18.335v8.801zm-6.807 9.31l6.223-6.223l12.965 12.965l-6.224 6.223z");
}

</style>
