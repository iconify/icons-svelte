<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j7k29qbyy"/><path class="z_356sbxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-user-duocolor-sharp" {...props}></Icon>
<style>
:global(.j7k29qbyy) {
  stroke-opacity: 0.4;
  d: path("M10 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0M8 21a4 4 0 1 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z_356sbxy) {
  d: path("m16 7l4 4v10H4V11l8-8z");
}

</style>
