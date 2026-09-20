<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gv5xmqiem"/><path class="qck_wensm"/><path class="wzx0dxb2r"/><path class="nuc2dr9ql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:circular-dep-outline-bold" {...props}></Icon>
<style>
:global(.gv5xmqiem) {
  d: path("M14.39 5.42a7 7 0 0 1 0 13.16");
}

:global(.nuc2dr9ql) {
  d: path("m12 16 -3 3 3 3");
}

:global(.qck_wensm) {
  d: path("M9.61 18.58a7 7 0 0 1 0 -13.16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wzx0dxb2r) {
  d: path("m12 2 3 3 -3 3");
}

</style>
