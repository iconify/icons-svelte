<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uz6rs8bdx"/><path class="xk_n26b7w"/><path class="zari_e5dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coat-hanger" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uz6rs8bdx) {
  d: path("M9.75 5A2.25 2.25 0 1 1 12 7.25v2");
}

:global(.xk_n26b7w) {
  d: path("m12.65 9.12l7.95 4.51q.65.37.65 1.12v2q0 .75-.65.38l-7.95-4.51q-.65-.37-1.3 0L3.4 17.13q-.65.37-.65-.38v-2q0-.75.65-1.12l7.95-4.51q.65-.37 1.3 0");
}

:global(.zari_e5dk) {
  d: path("M5.25 16.5v3.75h13.5V16.5");
}

</style>
