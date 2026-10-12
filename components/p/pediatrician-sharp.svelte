<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="hujf6nb_f"/><path class="q6_fpy0-m"/><path class="i_-4dlb6s"/><circle class="kelpoib0q"/><path class="bcgv-9gbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pediatrician-sharp" {...props}></Icon>
<style>
:global(.bcgv-9gbx) {
  d: path("M17.25 21.25v-3.5h4v3.5Z");
}

:global(.hujf6nb_f) {
  cx: 8.5px;
  cy: 5.75px;
  r: 2.5px;
}

:global(.i_-4dlb6s) {
  d: path("M6.5 11.5L6 15a2.5 2.5 0 0 0 5 0l-.5-3.5");
}

:global(.kelpoib0q) {
  cx: 19.25px;
  cy: 13.75px;
  r: 1.5px;
}

:global(.q6_fpy0-m) {
  d: path("M2.75 21.25V17a5.75 5.75 0 0 1 11.5 0v4.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
