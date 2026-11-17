<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gazr9eylw"/><path class="oeqtyzbxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gas-cylinder-duocolor-sharp" {...props}></Icon>
<style>
:global(.gazr9eylw) {
  stroke-opacity: 0.4;
  d: path("M8 7V3h8v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oeqtyzbxb) {
  d: path("M20 19H4v-8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4zM8 19v2h8v-2M4 13h16");
}

</style>
