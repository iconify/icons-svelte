<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="g828vzbqg"/><path class="klw3rnbnr"/><path class="stgudhffh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:candidate-podium-sharp" {...props}></Icon>
<style>
:global(.g828vzbqg) {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
}

:global(.klw3rnbnr) {
  d: path("M4.25 9.75h15.5v2.5H4.25zm3 2.5h9.5v9h-9.5v-1Z");
}

:global(.stgudhffh) {
  d: path("m12.14 15.07l.34.76l.14.32l.35.04l.82.08l.35.03l-.26.24l-.62.55l-.26.23l.07.35l.18.81l.07.34l-.3-.18l-.72-.41l-.3-.18l-.3.18l-.72.41l-.3.18l.07-.34l.18-.81l.07-.35l-.26-.23l-.62-.55l-.26-.24l.35-.03l.82-.08l.35-.04l.14-.32l.34-.76l.14-.32z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
