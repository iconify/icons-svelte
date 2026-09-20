<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jx5-n36vx"/><path class="qyfk67htz"/><path class="risyu_bcj"/><path class="cpjs7jb_n"/><path class="wvtsuii2m"/><path class="fkhwqab8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diff-text-outline-thin" {...props}></Icon>
<style>
:global(.cpjs7jb_n) {
  d: path("M8.5 6H21");
}

:global(.fkhwqab8s) {
  d: path("M8.5 18H21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jx5-n36vx) {
  d: path("M2.5 6h3");
}

:global(.qyfk67htz) {
  d: path("M4 4.5v3");
}

:global(.risyu_bcj) {
  d: path("M2.5 12h3");
}

:global(.wvtsuii2m) {
  d: path("M8.5 12H21");
}

</style>
