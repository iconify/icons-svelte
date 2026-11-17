<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ee1j9kb5s"/><path class="q63at12cl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:boolean-subtract-duotone-sharp" {...props}></Icon>
<style>
:global(.ee1j9kb5s) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h12v6H9v6H3Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.q63at12cl) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h12v6H9v6H3zm16 6h2v4m0 4v4h-4m-8-2v2h4");
}

</style>
