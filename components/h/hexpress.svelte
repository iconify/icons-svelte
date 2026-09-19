<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="idq5nwmru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hexpress" {...props}></Icon>
<style>
:global(.idq5nwmru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.41 9.07H14.28L5.71 23.9l8.57 14.83h17.13l8.56-14.83zm-9.08 6.13L15.1 27.83m15.48-7.73l-7.22 12.5m-4.64-11.09l8.25 4.78M6.28 34.21l5.3 9.19h10.61m0-39H11.58l-5.3 9.19m33.77 19.5l5.31-9.19l-5.31-9.19");
}

</style>
