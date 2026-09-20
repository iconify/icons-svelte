<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jzeve79sx"/><path class="j93aodlin"/><path class="rxwr8htky"/><path class="n88kwi36z"/><path class="nggkidbfu"/><path class="a5x_0nbah"/><path class="ymw3aibdo"/><path class="l2x-_sd5q"/><path class="l3ca9u8kt"/><path class="qp__wx2fk"/><path class="mp4vf7bic"/><path class="ati-ilbhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:graphql-duotone-thin" {...props}></Icon>
<style>
:global(.a5x_0nbah) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13.5 6.5 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ati-ilbhc) {
  d: path("m13.5 6.5 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j93aodlin) {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l2x-_sd5q) {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l3ca9u8kt) {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mp4vf7bic) {
  d: path("m10.5 6.5 -4 4");
}

:global(.n88kwi36z) {
  fill: currentColor;
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nggkidbfu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10.5 6.5 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qp__wx2fk) {
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rxwr8htky) {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
