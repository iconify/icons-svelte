<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nt-syvbnj"/><path class="jjfa9c8yk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-line-duocolor" {...props}></Icon>
<style>
:global(.jjfa9c8yk) {
  d: path("m3 16l4-4a1.414 1.414 0 0 1 2 0l2 2a1.414 1.414 0 0 0 2 0l8-8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nt-syvbnj) {
  stroke-opacity: 0.4;
  d: path("M3 4v14a2 2 0 0 0 2 2h16");
}

</style>
