<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nsn8ivtct"/><path class="a5yxnab-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-down-to-line-duocolor-round" {...props}></Icon>
<style>
:global(.a5yxnab-z) {
  d: path("m6 7l6 6l6-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nsn8ivtct) {
  stroke-opacity: 0.4;
  d: path("M6 17h12");
}

</style>
