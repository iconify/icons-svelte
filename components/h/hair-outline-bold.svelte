<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ahp9s2bzp"/><path class="qyottkbqu"/><path class="k6x6uv-ap"/><path class="h2va4xb2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hair-outline-bold" {...props}></Icon>
<style>
:global(.ahp9s2bzp) {
  d: path("M3 6h18v5H3Z");
}

:global(.h2va4xb2x) {
  d: path("M17 11v8");
}

:global(.k6x6uv-ap) {
  d: path("M12 11v8");
}

:global(.qyottkbqu) {
  d: path("M7 11v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
