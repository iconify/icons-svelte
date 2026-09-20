<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o9o4t05de"/><path class="ec-jcit8z"/><path class="ugs22v-bb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:course-outline-regular" {...props}></Icon>
<style>
:global(.ec-jcit8z) {
  d: path("M5 10h14v4H5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o9o4t05de) {
  d: path("M3 3h14v4H3Z");
}

:global(.ugs22v-bb) {
  d: path("M7 17h14v4H7Z");
}

</style>
