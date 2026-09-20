<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ckawxab4i"/><path class="zr5lbkq8n"/><path class="ujkepejes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mail-open-outline-bold" {...props}></Icon>
<style>
:global(.ckawxab4i) {
  d: path("m4 11 8 -8 8 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ujkepejes) {
  d: path("m6 12 6 6 6 -6");
}

:global(.zr5lbkq8n) {
  d: path("M4 11v10h16V11");
}

</style>
