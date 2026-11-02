<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ecy1zkb4e"/><path class="pctlsf99e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brush-duocolor-sharp" {...props}></Icon>
<style>
:global(.ecy1zkb4e) {
  stroke-opacity: 0.4;
  d: path("M10 3v3m4-3v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pctlsf99e) {
  d: path("M10 19v-5H6V3h12v11h-4v5a2 2 0 1 1-4 0m-4-9h12");
}

</style>
