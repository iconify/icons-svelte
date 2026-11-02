<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r769j7b0q"/><path class="mm4kkrtjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-yen-duocolor-round" {...props}></Icon>
<style>
:global(.mm4kkrtjd) {
  d: path("m6 5l6 6l6-6m-6 6v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r769j7b0q) {
  stroke-opacity: 0.4;
  d: path("M8 13h4m0 0h4m-8 4h4m0 0h4");
}

</style>
