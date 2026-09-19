<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dqdqw5b8p"/><path class="d2-qx-nbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:proton" {...props}></Icon>
<style>
:global(.d2-qx-nbw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.268 30.219A10.686 10.686 0 0 0 8.59 40.91v2.59");
}

:global(.dqdqw5b8p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.59 33.344V43.5h7.12v-9.717a3.56 3.56 0 0 1 3.56-3.564h7.3A12.86 12.86 0 0 0 26.568 4.5H8.59v12.695h7.12V11.21h10.378a6.084 6.084 0 0 1 0 12.168h-7.545a9.96 9.96 0 0 0-9.953 9.966");
}

</style>
