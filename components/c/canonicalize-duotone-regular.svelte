<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ic20sacjr"/><path class="oqki-x-zf"/><path class="u5jltjbuw"/><path class="oboujbbaa"/><path class="rdidnh2az"/><path class="ok9ioqb8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:canonicalize-duotone-regular" {...props}></Icon>
<style>
:global(.ic20sacjr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 5 3 3 3 -3 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oboujbbaa) {
  d: path("m3 5 3 3 3 -3 3 3 3 -3");
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.oqki-x-zf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 11.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rdidnh2az) {
  d: path("m10 11.5 2 2 2 -2");
}

:global(.u5jltjbuw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
