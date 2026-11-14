<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dif__6btx"/><path class="fn8qnfaaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ai-image-edit" {...props}></Icon>
<style>
:global(.dif__6btx) {
  d: path("M6 3h6.5A3.5 3.5 0 0 1 16 6.5v5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 3");
}

:global(.fn8qnfaaz) {
  d: path("m5.5 12l3.75-3.75L13 12m1.5 9.5v-2L20 14l2 2l-5.5 5.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
