<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iij8_24og"/><path class="rruu58b-y"/><path class="kfdmhd64i"/><path class="e4btx4zel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dose-missed-duotone-bold" {...props}></Icon>
<style>
:global(.e4btx4zel) {
  d: path("m21 15 -6 6");
}

:global(.iij8_24og) {
  fill: currentColor;
  d: path("m4 11 5 -5a3.5 3.5 0 0 1 5 5l-5 5a3.5 3.5 0 0 1 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.rruu58b-y) {
  d: path("m4 11 5 -5a3.5 3.5 0 0 1 5 5l-5 5a3.5 3.5 0 0 1 -5 -5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
