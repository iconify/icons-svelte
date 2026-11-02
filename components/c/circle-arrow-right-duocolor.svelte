<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bifj1rbsn"/><path class="q_a5zcbnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-right-duocolor" {...props}></Icon>
<style>
:global(.bifj1rbsn) {
  stroke-opacity: 0.4;
  d: path("m13 15l3-3l-3-3m3 3H8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q_a5zcbnk) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0");
}

</style>
