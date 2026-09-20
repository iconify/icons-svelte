<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k-f_lrb-e"/><path class="k5neb7b3k"/><path class="nlogjebfr"/><path class="rp0xo7l1b"/><path class="a0w40fbyp"/><path class="mlzwc7b5b"/><path class="kd8pirhpr"/><path class="crw18vrkk"/><path class="z-xixkiyt"/><path class="hspeog_hs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycle-duotone-bold" {...props}></Icon>
<style>
:global(.a0w40fbyp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 18 -4 -4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crw18vrkk) {
  d: path("m18 14 -5 5H9");
}

:global(.hspeog_hs) {
  d: path("m7 18 -4 -4 4 -4");
}

:global(.k-f_lrb-e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 14 5 -5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k5neb7b3k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 6.5 15 9l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kd8pirhpr) {
  d: path("M12.5 6.5 15 9l-2.5 2.5");
}

:global(.mlzwc7b5b) {
  d: path("m6 14 5 -5h4");
}

:global(.nlogjebfr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 14 -5 5H9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rp0xo7l1b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 16.5 9 19l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z-xixkiyt) {
  d: path("M11.5 16.5 9 19l2.5 2.5");
}

</style>
