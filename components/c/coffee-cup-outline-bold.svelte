<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zkx1g3b3t"/><path class="ghpezkxlh"/><path class="v3xsaib0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coffee-cup-outline-bold" {...props}></Icon>
<style>
:global(.ghpezkxlh) {
  d: path("M15 7a3 3 0 0 1 0 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v3xsaib0o) {
  d: path("M2 19h15");
}

:global(.zkx1g3b3t) {
  d: path("M4 7v9h11V7");
}

</style>
