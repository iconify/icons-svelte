<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mdyd30bgr"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="i92yi0bmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delta-metric-duotone-bold" {...props}></Icon>
<style>
:global(.i92yi0bmq) {
  d: path("m8 16 4 -4 4 4Z");
}

:global(.mdyd30bgr) {
  fill: currentColor;
  d: path("m8 16 4 -4 4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
