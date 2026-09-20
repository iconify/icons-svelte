<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="rw6ho_bav"/><path class="nnp9dj82w"/><path class="ybts533gz"/><path class="e3hgwus4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fact-table-outline-regular" {...props}></Icon>
<style>
:global(.e3hgwus4z) {
  d: path("M4.5 6.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nnp9dj82w) {
  d: path("M9 9v11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.ybts533gz) {
  d: path("M15 9v11");
}

</style>
