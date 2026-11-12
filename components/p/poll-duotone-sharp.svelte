<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qofi3ediw"/><path class="muww1dbxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:poll-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.muww1dbxg) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8-10h10M11 17h6");
}

:global(.qofi3ediw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 9a2 2 0 1 1-.001-3.999A2 2 0 0 1 5 9m0 10a2 2 0 1 1-.001-3.999A2 2 0 0 1 5 19");
}

</style>
