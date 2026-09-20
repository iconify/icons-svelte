<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i-zodcc2a"/><path class="x0l-yf_vd"/><path class="ox_kf9bfs"/><path class="x81m3s-aw"/><path class="r2-193ooz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-http-outline-bold" {...props}></Icon>
<style>
:global(.i-zodcc2a) {
  d: path("M16.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3h-5a3 3 0 0 1 -3 -3V7l3 -3Z");
}

:global(.ox_kf9bfs) {
  d: path("m8 6 3 3 -3 3");
}

:global(.r2-193ooz) {
  d: path("m5 12 -3 3 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x0l-yf_vd) {
  d: path("M2 9h9");
}

:global(.x81m3s-aw) {
  d: path("M2 15h9");
}

</style>
