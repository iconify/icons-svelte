<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jf60lda-p"/><path class="f4-a3xfdq"/><path class="hm-bgfqny"/><path class="xvlspstxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dishwasher" {...props}></Icon>
<style>
:global(.f4-a3xfdq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 7.25h16.5");
}

:global(.hm-bgfqny) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 5h.01");
}

:global(.jf60lda-p) {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.xvlspstxg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10.75h6m-6.25 4v3m3.25-3v3m3.25-3v3");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
