<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xlz01ub4s"/><path class="n3p0zmbop"/><path class="if5ft31dv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:more-vertical-outline-bold" {...props}></Icon>
<style>
:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.xlz01ub4s) {
  d: path("M11 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
