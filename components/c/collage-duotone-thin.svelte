<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o3pq64aer"/><path class="lia9jdrfo"/><path class="q4t0ntb4q"/><path class="eoxa-cb-h"/><path class="z67_1-j3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collage-duotone-thin" {...props}></Icon>
<style>
:global(.eoxa-cb-h) {
  d: path("M9 9h11v11H9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lia9jdrfo) {
  fill: currentColor;
  d: path("M9 9h11v11H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o3pq64aer) {
  fill: currentColor;
  d: path("M3 4h9v9H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q4t0ntb4q) {
  d: path("M3 4h9v9H3Z");
}

:global(.z67_1-j3c) {
  d: path("M14 3h7v4");
}

</style>
