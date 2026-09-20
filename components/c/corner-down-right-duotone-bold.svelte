<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqo7xjbdx"/><path class="lkcoizwse"/><path class="isvgtub8p"/><path class="xpi-ctm3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-down-right-duotone-bold" {...props}></Icon>
<style>
:global(.aqo7xjbdx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.isvgtub8p) {
  d: path("M4 4v10h16");
}

:global(.lkcoizwse) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 9 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xpi-ctm3k) {
  d: path("m15 9 5 5 -5 5");
}

</style>
