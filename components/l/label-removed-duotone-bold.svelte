<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fbde_z08y"/><path class="w3hyiobto"/><path class="iq8tuac7e"/><path class="wo_mlccql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:label-removed-duotone-bold" {...props}></Icon>
<style>
:global(.fbde_z08y) {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iq8tuac7e) {
  d: path("m10 11.5 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w3hyiobto) {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

:global(.wo_mlccql) {
  d: path("m14 11.5 -4 4");
}

</style>
