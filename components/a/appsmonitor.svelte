<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b03863b5g"/><path class="jq4h06tun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:appsmonitor" {...props}></Icon>
<style>
:global(.b03863b5g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8v16l8.32 7.268");
}

:global(.jq4h06tun) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 23.946a21.497 21.497 0 1 1-.001-.173");
}

</style>
