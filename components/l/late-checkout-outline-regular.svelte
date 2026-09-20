<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q7l4tcb1c"/><path class="gsq10_ixg"/><path class="w-w3xed8o"/><path class="e870_rb0s"/><path class="u146yqb3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:late-checkout-outline-regular" {...props}></Icon>
<style>
:global(.e870_rb0s) {
  d: path("M13.5 11.5v3");
}

:global(.gsq10_ixg) {
  d: path("M7 6h4v3H7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q7l4tcb1c) {
  d: path("M6 3h11l4 4v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2V5a2 2 0 0 1 2 -2");
}

:global(.u146yqb3r) {
  d: path("M13.5 14.5h3");
}

:global(.w-w3xed8o) {
  d: path("M10 14.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

</style>
