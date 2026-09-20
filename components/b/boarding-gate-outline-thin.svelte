<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pnevpfb0l"/><path class="cq8r84bse"/><path class="srslrxb7v"/><path class="l90ci7bpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:boarding-gate-outline-thin" {...props}></Icon>
<style>
:global(.cq8r84bse) {
  d: path("M20 21V4h-4v17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l90ci7bpu) {
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
}

:global(.pnevpfb0l) {
  d: path("M4 21V4h4v17");
}

:global(.srslrxb7v) {
  d: path("M10 12h4.5");
}

</style>
