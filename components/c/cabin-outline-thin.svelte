<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a6e_o0bju"/><path class="dvfmj91gv"/><path class="nl66y9men"/><path class="l4quinbfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cabin-outline-thin" {...props}></Icon>
<style>
:global(.a6e_o0bju) {
  d: path("m3 11 9 -9 9 9");
}

:global(.dvfmj91gv) {
  d: path("M6 11v10h12V11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l4quinbfm) {
  d: path("M16 6V3h3v3");
}

:global(.nl66y9men) {
  d: path("M6 16h12");
}

</style>
