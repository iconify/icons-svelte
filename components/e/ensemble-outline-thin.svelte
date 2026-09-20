<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tv_y06bgj"/><path class="liucm7_ra"/><path class="uxl9_oo-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ensemble-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.liucm7_ra) {
  d: path("m7 13 3 3 -3 3 -3 -3Z");
}

:global(.tv_y06bgj) {
  d: path("m12 3 3 3 -3 3 -3 -3Z");
}

:global(.uxl9_oo-x) {
  d: path("m17 13 3 3 -3 3 -3 -3Z");
}

</style>
