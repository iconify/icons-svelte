<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gcurcebny"/><path class="r3faxubne"/><path class="ws1d0fbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plate-outline-bold" {...props}></Icon>
<style>
:global(.gcurcebny) {
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ws1d0fbts) {
  d: path("M20 4v16");
}

</style>
