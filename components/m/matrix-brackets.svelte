<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwsgfbcwe"/><circle class="u1a9bn6oe"/><circle class="zczcnxb6y"/><circle class="frskmbb5i"/><circle class="ilmmol0fy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:matrix-brackets" {...props}></Icon>
<style>
:global(.frskmbb5i) {
  cx: 9.5px;
  cy: 15px;
  r: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ilmmol0fy) {
  cx: 14.5px;
  cy: 15px;
  r: 1.25px;
}

:global(.u1a9bn6oe) {
  cx: 9.5px;
  cy: 9px;
  r: 1.25px;
}

:global(.wwsgfbcwe) {
  d: path("M7.25 3.75H5.5a1 1 0 0 0-1 1v14.5a1 1 0 0 0 1 1h1.75m9.5-16.5h1.75a1 1 0 0 1 1 1v14.5a1 1 0 0 1-1 1h-1.75");
}

:global(.zczcnxb6y) {
  cx: 14.5px;
  cy: 9px;
  r: 1.25px;
}

</style>
