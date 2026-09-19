<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cw4adpb9e"/><path class="tuc4095vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bonify" {...props}></Icon>
<style>
:global(.cw4adpb9e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.35 19.083a19 19 0 1 1-13.497-13.45");
}

:global(.tuc4095vf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.019 19.291l6.363 7.127L43 5.612");
}

</style>
