<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dia4z7d4z"/><path class="s0216tidb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lane-arrow-straight-right" {...props}></Icon>
<style>
:global(.dia4z7d4z) {
  d: path("M9 21.5V3M4 8l5-5l5 5M9 20a5 5 0 0 1 5-5h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s0216tidb) {
  d: path("M16.5 11.5L20 15l-3.5 3.5");
}

</style>
