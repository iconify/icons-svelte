<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jn-s1-bbo"/><circle class="t4d76fbow"/><path class="c6l8r-bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bose-soundtouch" {...props}></Icon>
<style>
:global(.c6l8r-bqx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.742 34.06L9.213 10.642");
}

:global(.jn-s1-bbo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.73 8.125a27.06 27.06 0 0 1 27.057 0M15.82 15.209a18.88 18.88 0 0 1 18.877 0M19.91 22.293a10.7 10.7 0 0 1 10.697 0");
}

:global(.t4d76fbow) {
  cx: 17.293px;
  cy: 37.208px;
  r: 6.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
