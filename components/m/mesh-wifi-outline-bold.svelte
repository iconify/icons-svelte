<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wc595gblk"/><path class="bo88vlbuz"/><path class="e030h51ix"/><path class="elc06ob4j"/><path class="i2p3oabgb"/><path class="fiatxpbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mesh-wifi-outline-bold" {...props}></Icon>
<style>
:global(.bo88vlbuz) {
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.e030h51ix) {
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.elc06ob4j) {
  d: path("M8 8h8");
}

:global(.fiatxpbey) {
  d: path("m17 10 -4 4");
}

:global(.i2p3oabgb) {
  d: path("m7 10 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wc595gblk) {
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
