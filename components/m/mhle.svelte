<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vixf7ccbc"/><path class="u6n_qbbyr"/><path class="znq8keuip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mhle" {...props}></Icon>
<style>
:global(.u6n_qbbyr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.975 11.975h24.05v24.05h-24.05z");
}

:global(.vixf7ccbc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h37v37h-37z");
}

:global(.znq8keuip) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.988 17.988h12.025v12.025H17.988zM24 5.5v12.488M42.5 24H30.013M5.5 24h12.488M24 42.5V30.013");
}

</style>
