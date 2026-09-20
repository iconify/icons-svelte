<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q4t0ntb4q"/><path class="eoxa-cb-h"/><path class="z67_1-j3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collage-outline-bold" {...props}></Icon>
<style>
:global(.eoxa-cb-h) {
  d: path("M9 9h11v11H9Z");
}

:global(.q4t0ntb4q) {
  d: path("M3 4h9v9H3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z67_1-j3c) {
  d: path("M14 3h7v4");
}

</style>
