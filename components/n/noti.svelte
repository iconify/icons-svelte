<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hy0t9pbpv"/><path class="ytwgdxsik"/><path class="hzpqnlmob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:noti" {...props}></Icon>
<style>
:global(.hy0t9pbpv) {
  fill: currentColor;
  d: path("M30.656 25.77a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

:global(.hzpqnlmob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

:global(.ytwgdxsik) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.999 28.213V36.5m-12.44-11.68v9.917c0 .921.745 1.667 1.666 1.667h.5m-3.917-8.835h3.5m2.017-7.19V14.85c0-1.85-1.5-3.35-3.35-3.35h0a3.35 3.35 0 0 0-3.35 3.35h0m0 5.529V11.5m15.295 0a3.456 3.456 0 0 1 3.456 3.456v2.247a3.456 3.456 0 0 1-3.456 3.456h0a3.456 3.456 0 0 1-3.457-3.456v-2.247A3.456 3.456 0 0 1 29.92 11.5");
}

</style>
