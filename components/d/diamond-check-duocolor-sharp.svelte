<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k8s1leb8y"/><path class="fs89iqu4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-check-duocolor-sharp" {...props}></Icon>
<style>
:global(.fs89iqu4z) {
  d: path("m17 17l-5 5L2 12L12 2l10 10z");
}

:global(.k8s1leb8y) {
  stroke-opacity: 0.4;
  d: path("m9 12l2 2l4-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
