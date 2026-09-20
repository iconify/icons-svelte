<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dzi2rsuiu"/><path class="udwfiibqb"/><path class="n4s757but"/><path class="b8bt6fxoy"/><path class="scn6o5bwi"/><path class="nlc9pqruy"/><path class="jx5-n36vx"/><path class="qyfk67htz"/><path class="risyu_bcj"/><path class="cpjs7jb_n"/><path class="wvtsuii2m"/><path class="fkhwqab8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diff-text-duotone-bold" {...props}></Icon>
<style>
:global(.b8bt6fxoy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 6H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cpjs7jb_n) {
  d: path("M8.5 6H21");
}

:global(.dzi2rsuiu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2.5 6h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fkhwqab8s) {
  d: path("M8.5 18H21");
}

:global(.jx5-n36vx) {
  d: path("M2.5 6h3");
}

:global(.n4s757but) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nlc9pqruy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 18H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qyfk67htz) {
  d: path("M4 4.5v3");
}

:global(.risyu_bcj) {
  d: path("M2.5 12h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.scn6o5bwi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 12H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.udwfiibqb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wvtsuii2m) {
  d: path("M8.5 12H21");
}

</style>
