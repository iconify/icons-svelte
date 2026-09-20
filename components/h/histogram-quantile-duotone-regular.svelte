<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="g11phnbts"/><path class="f19wj-bda"/><path class="jj0sk4nef"/><path class="o9-mlwb2l"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4stwdjmu"/><path class="sok49cc0b"/><path class="hcn7bdzwu"/><path class="v9il_wb-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:histogram-quantile-duotone-regular" {...props}></Icon>
<style>
:global(.f19wj-bda) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g11phnbts) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hcn7bdzwu) {
  d: path("M15 11v7");
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jj0sk4nef) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o9-mlwb2l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.p4stwdjmu) {
  d: path("M7 13v5");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.sok49cc0b) {
  d: path("M11 8v10");
}

:global(.v9il_wb-q) {
  d: path("M6 10h12");
}

</style>
