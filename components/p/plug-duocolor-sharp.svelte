<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m-eanacma"/><path class="cpz5g02vr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plug-duocolor-sharp" {...props}></Icon>
<style>
:global(.cpz5g02vr) {
  d: path("M6 7h12v10H6Zm6 10v4");
}

:global(.m-eanacma) {
  stroke-opacity: 0.4;
  d: path("M9 3v4m6-4v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
