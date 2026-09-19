<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="lf8rf0bkr"/><circle class="hctngsbzk"/><path class="s87wzwb6q"/></g><path class="gdpz_rbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-fossify-29" {...props}></Icon>
<style>
:global(.gdpz_rbbn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

:global(.hctngsbzk) {
  cx: 28.195px;
  cy: 29.329px;
  r: 3.733px;
}

:global(.lf8rf0bkr) {
  d: path("M15.239 29.329c0-2.074 1.659-3.734 3.595-3.734s3.733 1.66 3.733 3.734c0 .968-.415 1.935-1.106 2.627c-1.521 1.244-6.222 4.84-6.222 4.84h7.328");
}

:global(.s87wzwb6q) {
  d: path("M24.877 35.413c.553.83 1.52 1.382 3.042 1.382h.276a3.72 3.72 0 0 0 3.733-3.733v-3.733");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
