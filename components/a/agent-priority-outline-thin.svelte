<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pp3du3b3p"/><path class="bjz8zacox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-priority-outline-thin" {...props}></Icon>
<style>
:global(.bjz8zacox) {
  d: path("M14.11 9.47a5 5 0 1 1 -4.22 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pp3du3b3p) {
  d: path("m7 7 5 -5 5 5");
}

</style>
