<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dytifdcql"/><path class="t4mkg0b6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.dytifdcql) {
  stroke-opacity: 0.4;
  d: path("M9 6a3 3 0 0 1 6 0v4M2 5l17 17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t4mkg0b6k) {
  d: path("M18 21H4V10h3m6 0h7v7");
}

</style>
