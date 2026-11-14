<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sb7ngsb2s"/><path class="ex1whdcrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:front-door" {...props}></Icon>
<style>
:global(.ex1whdcrj) {
  d: path("M8.75 5.5h3a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 7 8.75v-1.5A1.75 1.75 0 0 1 8.75 5.5m0 8h3a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 7 16.75v-1.5a1.75 1.75 0 0 1 1.75-1.75m8-1.5h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sb7ngsb2s) {
  d: path("M4 21.5v-19h16v19");
}

</style>
