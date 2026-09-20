<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="um18atgqz"/><path class="rpurvpt1e"/><path class="qdz4_8j8r"/><path class="ky4omnbla"/><path class="l0v-b4kbr"/><path class="az5esj3_g"/><path class="d_yxl29go"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:loan-duotone-bold" {...props}></Icon>
<style>
:global(.az5esj3_g) {
  d: path("M10.5 9.5 8 12l2.5 2.5");
}

:global(.d_yxl29go) {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

:global(.ky4omnbla) {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.qdz4_8j8r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 9.5 16 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rpurvpt1e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 9.5 8 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t4wfbu4kp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.um18atgqz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
