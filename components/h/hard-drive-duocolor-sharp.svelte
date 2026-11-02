<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m975t8b7k"/><path class="mll_tgbpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hard-drive-duocolor-sharp" {...props}></Icon>
<style>
:global(.m975t8b7k) {
  stroke-opacity: 0.4;
  d: path("M7 16h.01M11 16h.01");
}

:global(.mll_tgbpg) {
  d: path("m3 13l4-8h10l4 8v6H3zm0 0h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
