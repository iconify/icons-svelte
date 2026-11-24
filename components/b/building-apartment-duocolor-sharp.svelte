<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hzl1vcbao"/><path class="b0ytxn-0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-apartment-duocolor-sharp" {...props}></Icon>
<style>
:global(.b0ytxn-0j) {
  d: path("M3 21h18M7 21V4h10v17M10 8h.01M14 8h.01M10 12h.01M14 12h.01");
}

:global(.hzl1vcbao) {
  stroke-opacity: 0.4;
  d: path("M10 21v-4h4v4M7 11H3v10m14-10h4v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
