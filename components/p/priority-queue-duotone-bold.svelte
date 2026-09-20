<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ei8gh2b1p"/><path class="e1s3hcbto"/><path class="sw042-lbz"/><path class="ep60chbts"/><path class="ffi6qkohm"/><path class="zuuudpbwi"/><path class="kh31pt5af"/><path class="t99bgtbzx"/><path class="ecismzb4h"/><path class="mo-r4ib5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:priority-queue-duotone-bold" {...props}></Icon>
<style>
:global(.e1s3hcbto) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ecismzb4h) {
  d: path("M20 15V9");
}

:global(.ei8gh2b1p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ep60chbts) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 15V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffi6qkohm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 11 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kh31pt5af) {
  d: path("M3 13h14");
}

:global(.mo-r4ib5t) {
  d: path("m18 11 2 -2 2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sw042-lbz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t99bgtbzx) {
  d: path("M3 18h14");
}

:global(.zuuudpbwi) {
  d: path("M3 8h14");
}

</style>
