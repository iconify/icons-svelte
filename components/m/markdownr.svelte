<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s2_5fxp3u"/><path class="vjiavwb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:markdownr" {...props}></Icon>
<style>
:global(.s2_5fxp3u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 32.597V15.403l8.597 17.194l8.598-17.194v17.194m4.137-3.755v3.756H43v-3.756");
}

:global(.vjiavwb4d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.264 23.262l6.134 6.116l6.492-6.116h-3.684v-6.903H31.59v6.903Z");
}

</style>
