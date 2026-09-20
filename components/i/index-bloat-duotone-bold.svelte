<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="b0fjnzegu"/><path class="eqqtl6brn"/><path class="c8pjjlblu"/><path class="r75i-u67u"/><path class="crv4i00bu"/><path class="wwb_9fbub"/><path class="je5qtm2zh"/><path class="g1xwr4cnp"/><path class="t2ilqxxwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-bloat-duotone-bold" {...props}></Icon>
<style>
:global(.b0fjnzegu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c8pjjlblu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.eqqtl6brn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g1xwr4cnp) {
  d: path("M4 14h15");
}

:global(.je5qtm2zh) {
  d: path("M4 10h17");
}

:global(.qn-h03e3f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r75i-u67u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t2ilqxxwv) {
  d: path("M4 18h8");
}

:global(.wwb_9fbub) {
  d: path("M4 6h12");
}

</style>
