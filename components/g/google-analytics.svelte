<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ras6scpfa"/><circle class="eokpm4bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:google-analytics" {...props}></Icon>
<style>
:global(.eokpm4bio) {
  cx: 10.5px;
  cy: 37.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ras6scpfa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 42.5a5 5 0 0 0 5-5v-27a5 5 0 0 0-5-5h0a5 5 0 0 0-5 5v27a5 5 0 0 0 5 5m-13.5 0a5 5 0 0 0 5-5v-16a5 5 0 0 0-5-5h0a5 5 0 0 0-5 5v16a5 5 0 0 0 5 5");
}

</style>
