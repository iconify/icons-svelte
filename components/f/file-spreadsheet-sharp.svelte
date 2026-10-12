<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s43l187bp"/><path class="x8ps3ed8u"/><path class="kpyw03bwl"/><path class="m7nn5i96h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-spreadsheet-sharp" {...props}></Icon>
<style>
:global(.kpyw03bwl) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 10.5h.01m3.74 0h.01");
}

:global(.m7nn5i96h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 13.75h7.5v4.5h-7.5Zm3 0v4.5");
}

:global(.s43l187bp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.x8ps3ed8u) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v5.5h5.5");
}

</style>
