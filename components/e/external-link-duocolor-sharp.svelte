<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="phvznzb4o"/><path class="mhbbxrb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:external-link-duocolor-sharp" {...props}></Icon>
<style>
:global(.mhbbxrb0o) {
  d: path("M10 5H5v14h14v-5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.phvznzb4o) {
  stroke-opacity: 0.4;
  d: path("M15 4h5v5m0-5l-7 7");
}

</style>
