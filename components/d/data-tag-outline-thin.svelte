<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5icmybsm"/><path class="n3p0zmbop"/><path class="c-vnm8iux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-tag-outline-thin" {...props}></Icon>
<style>
:global(.c-vnm8iux) {
  d: path("M15 12h3");
}

:global(.c5icmybsm) {
  d: path("m4 12 6 -6h10v12H10Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
