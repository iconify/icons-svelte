<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yw0xzbbmi"/><path class="n3p0zmbop"/><path class="knng32dgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:more-horizontal-outline-bold" {...props}></Icon>
<style>
:global(.knng32dgc) {
  d: path("M18 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yw0xzbbmi) {
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
