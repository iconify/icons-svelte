<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tkntuhbzi"/><path class="c5_wc7b7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-duocolor" {...props}></Icon>
<style>
:global(.c5_wc7b7b) {
  d: path("M4 15c6-3 10 3 16 0V4C14 7 10 1 4 4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tkntuhbzi) {
  stroke-opacity: 0.4;
  d: path("M4 15v6");
}

</style>
