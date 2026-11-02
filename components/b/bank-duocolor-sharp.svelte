<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k8k5xbcwl"/><path class="trn17c93q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bank-duocolor-sharp" {...props}></Icon>
<style>
:global(.k8k5xbcwl) {
  stroke-opacity: 0.4;
  d: path("M6 11v6m4-6v6m4-6v6m4-6v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.trn17c93q) {
  d: path("m12 3l9 4H3zM3 21h18");
}

</style>
