<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="h2s9k9bqy"/><path class="rwf38yblb"/><path class="axcnbfdgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huckleberry" {...props}></Icon>
<style>
:global(.axcnbfdgy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.767a5.6 5.6 0 0 0-5.602-5.602H5.5a5.6 5.6 0 0 0 5.603 5.602z");
}

:global(.h2s9k9bqy) {
  cx: 24px;
  cy: 26.801px;
  r: 15.034px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.rwf38yblb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.767a5.6 5.6 0 0 1 5.603-5.602H42.5a5.6 5.6 0 0 1-5.602 5.602z");
}

</style>
