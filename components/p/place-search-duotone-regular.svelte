<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p67gkiiyp"/><path class="ieioa6bqm"/><path class="qad3kqbgr"/><path class="hob4evbuj"/><path class="hrabrxb6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:place-search-duotone-regular" {...props}></Icon>
<style>
:global(.hob4evbuj) {
  d: path("M9 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hrabrxb6m) {
  d: path("M11.5 9.5 15 13");
}

:global(.ieioa6bqm) {
  fill: currentColor;
  d: path("M9 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p67gkiiyp) {
  fill: currentColor;
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qad3kqbgr) {
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
}

</style>
