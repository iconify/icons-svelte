<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="di40i1kbs"/><path class="ok_o2hnik"/><path class="wik6klbxn"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p86p59b-c"/><path class="d-23-qb2d"/><path class="ip4hr0bew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-column-decreasing-duotone-regular" {...props}></Icon>
<style>
:global(.d-23-qb2d) {
  d: path("M13 11v9");
}

:global(.di40i1kbs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ip4hr0bew) {
  d: path("M18 15v5");
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.ok_o2hnik) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p86p59b-c) {
  d: path("M8 7v13");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.wik6klbxn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
