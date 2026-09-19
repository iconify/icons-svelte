<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gywjucctc"/><path class="yj2ht1bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:boorusphere" {...props}></Icon>
<style>
:global(.gywjucctc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.038 42.5c.183-16.554 9.914-20.46 17.556-22.449c14.448-3.76 21.064 13.1 5.113 22.449z");
}

:global(.yj2ht1bak) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.038 42.5V18.34c0-7.656 7.03-12.912 13.873-12.84c11.08.119 9.326 9.055 9.77 14.183");
}

</style>
