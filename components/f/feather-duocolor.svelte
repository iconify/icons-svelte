<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="odh-gj0dg"/><path class="nkoja3b2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:feather-duocolor" {...props}></Icon>
<style>
:global(.nkoja3b2g) {
  d: path("M13 5a4.243 4.243 0 0 1 6 6l-6 6H7v-6Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.odh-gj0dg) {
  stroke-opacity: 0.4;
  d: path("M4 20L16 8m1 5h-6");
}

</style>
