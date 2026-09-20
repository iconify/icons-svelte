<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wt76_hbmn"/><path class="l9cf9bbmd"/><path class="plqv1xi7k"/><path class="j_z-vb9qy"/><path class="xvmft_b5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logout-all-outline-bold" {...props}></Icon>
<style>
:global(.j_z-vb9qy) {
  d: path("M10 15h10");
}

:global(.l9cf9bbmd) {
  d: path("M10 9h10");
}

:global(.plqv1xi7k) {
  d: path("M17.5 6.5 20 9l-2.5 2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wt76_hbmn) {
  d: path("M9 3H3v18h6");
}

:global(.xvmft_b5k) {
  d: path("M17.5 12.5 20 15l-2.5 2.5");
}

</style>
