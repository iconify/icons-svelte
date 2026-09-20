<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="km9uii_ku"/><path class="srh2bsbhr"/><path class="t5e6ypb-u"/><path class="ri2m-q_tv"/><path class="wwogglmvt"/><path class="lpz1dcbuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rollback-auto-duotone-bold" {...props}></Icon>
<style>
:global(.km9uii_ku) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lpz1dcbuc) {
  d: path("M11.5 9.5 9 12l2.5 2.5");
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.srh2bsbhr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t5e6ypb-u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 9.5 9 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wwogglmvt) {
  d: path("M9 12h8");
}

</style>
