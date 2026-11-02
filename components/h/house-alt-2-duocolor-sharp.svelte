<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ra34vcrze"/><path class="ldyizlhnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-2-duocolor-sharp" {...props}></Icon>
<style>
:global(.ldyizlhnj) {
  d: path("M3 20h18M5 20v-9l7-7l7 7v9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ra34vcrze) {
  stroke-opacity: 0.4;
  d: path("M10 20v-4a2 2 0 1 1 4 0v4");
}

</style>
