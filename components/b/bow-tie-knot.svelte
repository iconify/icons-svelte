<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xi1rx4wyk"/><path class="or30f3rrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bow-tie-knot" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.or30f3rrs) {
  d: path("M11 7L9 18l3 3.5l3-3.5l-2-11");
}

:global(.xi1rx4wyk) {
  d: path("M11.921 3h.158a1.5 1.5 0 0 1 1.455 1.864l-.291 1.166A1.28 1.28 0 0 1 12 7a1.28 1.28 0 0 1-1.243-.97l-.291-1.166A1.5 1.5 0 0 1 11.921 3");
}

</style>
