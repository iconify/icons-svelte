<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bazq81bsf"/><path class="hwy5g2bde"/><path class="emxd-h1xw"/><path class="d3xn50bni"/><path class="oy7fa3gbk"/><path class="m0wg_2sjy"/><path class="xoh5qp2um"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:phrasebook-duotone-bold" {...props}></Icon>
<style>
:global(.bazq81bsf) {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d3xn50bni) {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.emxd-h1xw) {
  fill: currentColor;
  d: path("M11 14v4h3.5v-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hwy5g2bde) {
  fill: currentColor;
  d: path("M11 7v4h3.5V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m0wg_2sjy) {
  d: path("M11 7v4h3.5V7Z");
}

:global(.oy7fa3gbk) {
  d: path("M8 2v20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xoh5qp2um) {
  d: path("M11 14v4h3.5v-4Z");
}

</style>
