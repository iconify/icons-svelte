<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z3ru5llvg"/><path class="fadcahsis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-unread-outline-bold" {...props}></Icon>
<style>
:global(.fadcahsis) {
  d: path("M18 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z3ru5llvg) {
  d: path("M13.96 6.66a7 7 0 1 1 -5.92 0");
}

</style>
