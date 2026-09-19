<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tlkm1kbkl"/><path class="rlk4o-xsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:loopboard" {...props}></Icon>
<style>
:global(.rlk4o-xsp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.701 5.68l-6.82 6.82l6.82 6.82");
}

:global(.tlkm1kbkl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.72 12.5H16A11.5 11.5 0 0 0 4.5 24h0A11.5 11.5 0 0 0 16 35.5h16A11.5 11.5 0 0 0 43.5 24h0A11.5 11.5 0 0 0 32 12.5H21.881");
}

</style>
