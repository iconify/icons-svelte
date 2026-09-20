<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ce7y3gbnp"/><path class="yi8fe_bcj"/><path class="u-kmlrghs"/><path class="jsdtqkbqb"/><path class="qvqg3kbvw"/><path class="b3s4djbny"/><path class="mw6526b2i"/><path class="sxlwlmkmh"/><path class="eskbyryvt"/><path class="hc7fbd-jo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grad-flow-duotone-regular" {...props}></Icon>
<style>
:global(.b3s4djbny) {
  d: path("M4 5h16");
}

:global(.ce7y3gbnp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eskbyryvt) {
  d: path("m10 14.5 2 2 2 -2");
}

:global(.hc7fbd-jo) {
  d: path("M4 19h16");
}

:global(.jsdtqkbqb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 14.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mw6526b2i) {
  d: path("m10 7.5 2 2 2 -2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvqg3kbvw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 19h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.u-kmlrghs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yi8fe_bcj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 7.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
