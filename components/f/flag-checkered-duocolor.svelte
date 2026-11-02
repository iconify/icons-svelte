<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bli7l-qys"/><path class="kpj7-0bup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-checkered-duocolor" {...props}></Icon>
<style>
:global(.bli7l-qys) {
  stroke-opacity: 0.4;
  d: path("M4 10c6-3 10 3 16 0M9 4v10m6-9v10");
}

:global(.kpj7-0bup) {
  d: path("M4 15c6-3 10 3 16 0V4C14 7 10 1 4 4Zm0 0v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
