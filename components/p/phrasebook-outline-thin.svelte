<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d3xn50bni"/><path class="oy7fa3gbk"/><path class="m0wg_2sjy"/><path class="xoh5qp2um"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:phrasebook-outline-thin" {...props}></Icon>
<style>
:global(.d3xn50bni) {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0wg_2sjy) {
  d: path("M11 7v4h3.5V7Z");
}

:global(.oy7fa3gbk) {
  d: path("M8 2v20");
}

:global(.xoh5qp2um) {
  d: path("M11 14v4h3.5v-4Z");
}

</style>
