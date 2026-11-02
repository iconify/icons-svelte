<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w9j05kbxw"/><path class="rr43ghbwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:desktop-tower-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rr43ghbwd) {
  d: path("M13 8a4 4 0 1 1 8 0v8a4 4 0 1 1-8 0Zm0 1H7a4 4 0 1 0 0 8h6m4-9h.01M17 13v3");
}

:global(.w9j05kbxw) {
  stroke-opacity: 0.4;
  d: path("M6 20h3");
}

</style>
