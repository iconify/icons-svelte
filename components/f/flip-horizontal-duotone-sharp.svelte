<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="in7wbdcvj"/><path class="vg0cldu-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flip-horizontal-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.in7wbdcvj) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.707 11.293a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 2 17V7a1.002 1.002 0 0 1 1.707-.707ZM22 7v10a1.002 1.002 0 0 1-1.707.707l-5-5a1 1 0 0 1 0-1.414l5-5A1 1 0 0 1 22 7");
}

:global(.vg0cldu-e) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 7l5 5l-5 5zm9-2v2m0 4v2m0 4v2m9-12l-5 5l5 5z");
}

</style>
