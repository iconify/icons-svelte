<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dwltyfb3p"/><path class="xwbv0l_7u"/><path class="sqk_bfbxp"/><path class="ncr6vm62v"/><path class="l5r0hwbum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prompt-stuffing-outline-regular" {...props}></Icon>
<style>
:global(.dwltyfb3p) {
  d: path("M2 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.l5r0hwbum) {
  d: path("m18 10 3 3 -3 3");
}

:global(.ncr6vm62v) {
  d: path("M4 16h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sqk_bfbxp) {
  d: path("M4 13h8");
}

:global(.xwbv0l_7u) {
  d: path("M4 10h8");
}

</style>
