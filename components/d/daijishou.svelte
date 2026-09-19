<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mraibzbwh"/><path class="xzlar5b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:daijishou" {...props}></Icon>
<style>
:global(.mraibzbwh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.37 17.875L24 11.466l-6.37 6.409zm0 12.189L24 36.8l-6.37-6.736z");
}

:global(.xzlar5b_m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.413 25.913L24 44.5l18.587-18.587zM42.75 22.25L24 3.5L5.25 22.25z");
}

</style>
