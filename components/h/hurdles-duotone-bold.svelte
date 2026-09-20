<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nu0ti3ggl"/><path class="tw9fmib1q"/><path class="xjc8r-b1m"/><path class="qz9_3ub7s"/><path class="vhnbtvbtn"/><path class="pb147jbda"/><path class="wfoy3xxos"/><path class="dznv025mt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hurdles-duotone-bold" {...props}></Icon>
<style>
:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.nu0ti3ggl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pb147jbda) {
  d: path("M6 8v12");
}

:global(.qz9_3ub7s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tw9fmib1q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.wfoy3xxos) {
  d: path("M18 8v12");
}

:global(.xjc8r-b1m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
