<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v2mnclz8q"/><path class="p59qmd_pn"/><path class="a-2786bge"/><path class="ovlj_c6ad"/><path class="n_sq8uh7x"/><path class="d_b1a31kv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:horse-riding-duotone-bold" {...props}></Icon>
<style>
:global(.a-2786bge) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d_b1a31kv) {
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n_sq8uh7x) {
  d: path("M8 12h9");
}

:global(.ovlj_c6ad) {
  d: path("M5 21v-8c0 -4 3 -7 7 -7h2.5l3 -3v5c2 2 2.5 4 2.5 7v6");
}

:global(.p59qmd_pn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 21v-8c0 -4 3 -7 7 -7h2.5l3 -3v5c2 2 2.5 4 2.5 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v2mnclz8q) {
  fill: currentColor;
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
