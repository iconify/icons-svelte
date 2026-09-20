<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x0z-ob3sw"/><path class="ixh9awbgs"/><path class="f57qnnn4v"/><path class="zs3i_yb5e"/><path class="ac8x62bjn"/><path class="mh6qj7a-f"/><path class="jx5-n36vx"/><path class="qyfk67htz"/><path class="risyu_bcj"/><path class="cpjs7jb_n"/><path class="wvtsuii2m"/><path class="fkhwqab8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diff-text-duotone-thin" {...props}></Icon>
<style>
:global(.ac8x62bjn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 12H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cpjs7jb_n) {
  d: path("M8.5 6H21");
}

:global(.f57qnnn4v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.ixh9awbgs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jx5-n36vx) {
  d: path("M2.5 6h3");
}

:global(.mh6qj7a-f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 18H21");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.x0z-ob3sw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2.5 6h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zs3i_yb5e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 6H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
