<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tdh9yg50t"/><path class="lzphm4byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:grammarly" {...props}></Icon>
<style>
:global(.lzphm4byp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m44.759 39.447l-1.299-6.295l-6.294 1.299");
}

:global(.tdh9yg50t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.46 33.152a21.5 21.5 0 1 1 .004-18.297");
}

</style>
