<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b3s4djbny"/><path class="mw6526b2i"/><path class="sxlwlmkmh"/><path class="eskbyryvt"/><path class="hc7fbd-jo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grad-flow-outline-thin" {...props}></Icon>
<style>
:global(.b3s4djbny) {
  d: path("M4 5h16");
}

:global(.eskbyryvt) {
  d: path("m10 14.5 2 2 2 -2");
}

:global(.hc7fbd-jo) {
  d: path("M4 19h16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mw6526b2i) {
  d: path("m10 7.5 2 2 2 -2");
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

</style>
