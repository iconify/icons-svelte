<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kn-4tic2i"/><path class="t8qnl-bvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:page-turn-outline-regular" {...props}></Icon>
<style>
:global(.kn-4tic2i) {
  d: path("M4 21V3h10l6 6v12Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t8qnl-bvo) {
  d: path("M14 3v6h6");
}

</style>
