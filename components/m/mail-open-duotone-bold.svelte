<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="teqd5v2_o"/><path class="c1ux3mb1i"/><path class="fqmq1tb6q"/><path class="ckawxab4i"/><path class="zr5lbkq8n"/><path class="ujkepejes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mail-open-duotone-bold" {...props}></Icon>
<style>
:global(.c1ux3mb1i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11v10h16V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ckawxab4i) {
  d: path("m4 11 8 -8 8 8");
}

:global(.fqmq1tb6q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 12 6 6 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.teqd5v2_o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 11 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ujkepejes) {
  d: path("m6 12 6 6 6 -6");
}

:global(.zr5lbkq8n) {
  d: path("M4 11v10h16V11");
}

</style>
