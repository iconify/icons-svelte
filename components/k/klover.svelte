<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s5nvho_hy"/><path class="nfbte06lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:klover" {...props}></Icon>
<style>
:global(.nfbte06lp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.69 7.875v21.498l18.622 10.751V18.622z");
}

:global(.s5nvho_hy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5L5.381 13.25v21.5L24 45.5l18.619-10.75v-21.5z");
}

</style>
