<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ljwonn_4x"/><path class="u0bqerbxy"/><path class="ael42ebyo"/><path class="kr12j6b1h"/><path class="too3-lbua"/><path class="c54e_8bfi"/><path class="rqo45wl3s"/><path class="iob1atbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:border-24-filled" {...props}></Icon>
<style>
:global(.ael42ebyo) {
  d: path("M19 11a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0v-2z");
  fill: currentColor;
}

:global(.c54e_8bfi) {
  d: path("M18 3a1 1 0 1 0 0 2a1 1 0 0 1 1 1a1 1 0 1 0 2 0a3 3 0 0 0-3-3z");
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iob1atbyp) {
  d: path("M18 21a1 1 0 1 1 0-2a1 1 0 0 0 1-1a1 1 0 1 1 2 0a3 3 0 0 1-3 3z");
  fill: currentColor;
}

:global(.kr12j6b1h) {
  d: path("M13 21a1 1 0 1 0 0-2h-2a1 1 0 1 0 0 2h2z");
  fill: currentColor;
}

:global(.ljwonn_4x) {
  d: path("M14 4a1 1 0 0 1-1 1h-2a1 1 0 1 1 0-2h2a1 1 0 0 1 1 1z");
  fill: currentColor;
}

:global(.rqo45wl3s) {
  d: path("M7 20a1 1 0 0 1-1 1a3 3 0 0 1-3-3a1 1 0 1 1 2 0a1 1 0 0 0 1 1a1 1 0 0 1 1 1z");
  fill: currentColor;
}

:global(.too3-lbua) {
  d: path("M7 4a1 1 0 0 0-1-1a3 3 0 0 0-3 3a1 1 0 0 0 2 0a1 1 0 0 1 1-1a1 1 0 0 0 1-1z");
  fill: currentColor;
}

:global(.u0bqerbxy) {
  d: path("M5 11a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0v-2z");
  fill: currentColor;
}

</style>
