<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tv_y06bgj"/><path class="liucm7_ra"/><path class="uxl9_oo-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ensemble-outline-bold" {...props}></Icon>
<style>
:global(.liucm7_ra) {
  d: path("m7 13 3 3 -3 3 -3 -3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tv_y06bgj) {
  d: path("m12 3 3 3 -3 3 -3 -3Z");
}

:global(.uxl9_oo-x) {
  d: path("m17 13 3 3 -3 3 -3 -3Z");
}

</style>
