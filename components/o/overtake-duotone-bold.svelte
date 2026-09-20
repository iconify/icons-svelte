<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t830b32gy"/><path class="x-7dxbcyu"/><path class="ln_5yacac"/><path class="hhwp_ccfq"/><path class="ddx1lo_hx"/><path class="nbr7qebnn"/><path class="hcn-wubvk"/><path class="toy0nxbdm"/><path class="ler50rfbf"/><path class="caiwqabfd"/><path class="qw9zcf0wd"/><path class="beunabbsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overtake-duotone-bold" {...props}></Icon>
<style>
:global(.beunabbsv) {
  d: path("M12.5 6.5 15 4l2.5 2.5");
}

:global(.caiwqabfd) {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

:global(.ddx1lo_hx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hcn-wubvk) {
  d: path("M3 2v20");
}

:global(.hhwp_ccfq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.5 10.5 9 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ler50rfbf) {
  d: path("M9 8v12");
}

:global(.ln_5yacac) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nbr7qebnn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 6.5 15 4l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qw9zcf0wd) {
  d: path("M15 4v12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t830b32gy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.toy0nxbdm) {
  d: path("M21 2v20");
}

:global(.x-7dxbcyu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
