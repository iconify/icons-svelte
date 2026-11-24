<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i5w95gbde"/><path class="n4fw95b9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pyramid-duocolor-sharp" {...props}></Icon>
<style>
:global(.i5w95gbde) {
  stroke-opacity: 0.4;
  d: path("m12 5l4 15");
}

:global(.n4fw95b9v) {
  d: path("m12 5l10 15H2z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
