<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w7o4ylt6h"/><path class="c2k5-kblh"/><path class="d45kg_ien"/><path class="y29zmn0-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plastic-free-duotone-bold" {...props}></Icon>
<style>
:global(.c2k5-kblh) {
  d: path("M9 8v12h6V8Z");
}

:global(.d45kg_ien) {
  d: path("M10.5 8V4h3v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w7o4ylt6h) {
  fill: currentColor;
  d: path("M9 8v12h6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y29zmn0-m) {
  d: path("M5 20 19 6");
}

</style>
