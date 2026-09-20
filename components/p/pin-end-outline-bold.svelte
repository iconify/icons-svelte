<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qad3kqbgr"/><path class="gvs6g-b0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pin-end-outline-bold" {...props}></Icon>
<style>
:global(.gvs6g-b0k) {
  d: path("M9.5 7.5h5v5h-5Z");
}

:global(.qad3kqbgr) {
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
