<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uhfv81bjt"/><path class="pq9ly31-r"/><path class="szshe-6ah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:party-hat-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pq9ly31-r) {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.szshe-6ah) {
  d: path("M7 17h10");
}

:global(.uhfv81bjt) {
  d: path("M5 20c2 -6 5 -10 7 -14 2 4 5 8 7 14Z");
}

</style>
