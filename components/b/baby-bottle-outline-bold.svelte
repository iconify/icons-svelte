<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wdl213b6n"/><path class="cfd43lbgp"/><path class="yhnjhi90f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:baby-bottle-outline-bold" {...props}></Icon>
<style>
:global(.cfd43lbgp) {
  d: path("M7 13h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wdl213b6n) {
  d: path("M7 21V9h10v12Z");
}

:global(.yhnjhi90f) {
  d: path("M10 9V6.5a2 2 0 0 1 4 0V9");
}

</style>
