<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-cu8wbhl"/><path class="t6bqz9mcc"/><path class="aszec0xzq"/><path class="o22a_hbrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bread-duotone-thin" {...props}></Icon>
<style>
:global(.aszec0xzq) {
  d: path("m9 11 2 -2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-cu8wbhl) {
  fill: currentColor;
  d: path("M4 20v-7c0 -4 3 -6 8 -6s8 2 8 6v7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o22a_hbrn) {
  d: path("m13 11 2 -2");
}

:global(.t6bqz9mcc) {
  d: path("M4 20v-7c0 -4 3 -6 8 -6s8 2 8 6v7Z");
}

</style>
