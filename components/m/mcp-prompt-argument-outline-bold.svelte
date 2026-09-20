<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_qzku-2n"/><path class="s09hy0b0y"/><path class="xq_z6abtw"/><path class="wv2epfb5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-prompt-argument-outline-bold" {...props}></Icon>
<style>
:global(.s_qzku-2n) {
  d: path("M14 5h4a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8l3 -3h4");
}

:global(.s09hy0b0y) {
  d: path("M7 11h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wv2epfb5m) {
  d: path("M14 15h3");
}

:global(.xq_z6abtw) {
  d: path("M7 15h4");
}

</style>
