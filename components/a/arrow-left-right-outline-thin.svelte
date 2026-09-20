<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxlwlmkmh"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-left-right-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzsvawc8s) {
  d: path("m8 8 -4 4 4 4");
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.u8aszkb6i) {
  d: path("m16 8 4 4 -4 4");
}

</style>
