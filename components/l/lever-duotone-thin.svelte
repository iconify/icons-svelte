<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kxpwvtbvr"/><path class="dzijgfbaz"/><path class="ubqbpfbgm"/><path class="ia8_hqb_h"/><path class="ss_efzbzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lever-duotone-thin" {...props}></Icon>
<style>
:global(.dzijgfbaz) {
  fill: currentColor;
  d: path("M16 6h5v5h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ia8_hqb_h) {
  d: path("m9 14 5 5H4Z");
}

:global(.kxpwvtbvr) {
  fill: currentColor;
  d: path("m9 14 5 5H4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ss_efzbzj) {
  d: path("M16 6h5v5h-5Z");
}

:global(.ubqbpfbgm) {
  d: path("m3 8 6 6h12");
}

</style>
