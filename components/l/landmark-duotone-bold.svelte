<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o17dzpf1f"/><path class="d4v3t3bns"/><path class="g91uwsb-i"/><path class="mjsa21byd"/><path class="ok9ioqb8x"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:landmark-duotone-bold" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.d4v3t3bns) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g91uwsb-i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mjsa21byd) {
  d: path("M8 17V7l4 -4 4 4v10");
}

:global(.o17dzpf1f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17V7l4 -4 4 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
