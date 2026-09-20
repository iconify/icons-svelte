<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ns53blbaz"/><path class="d4dvqacly"/><path class="gv3c38hmw"/><path class="egganu2-z"/><path class="j9epvsb_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:molecule-outline-regular" {...props}></Icon>
<style>
:global(.d4dvqacly) {
  d: path("M10 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.egganu2-z) {
  d: path("m8 14 3 -3");
}

:global(.gv3c38hmw) {
  d: path("M16 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.j9epvsb_e) {
  d: path("m15 11 2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ns53blbaz) {
  d: path("M3 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
