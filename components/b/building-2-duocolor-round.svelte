<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f3pn-qbhe"/><path class="q73c0pb0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-2-duocolor-round" {...props}></Icon>
<style>
:global(.f3pn-qbhe) {
  stroke-opacity: 0.4;
  d: path("m12 10.6l.126-.1a3 3 0 0 1 3.748 0l1.625 1.299A4 4 0 0 1 19 14.923V20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q73c0pb0w) {
  d: path("M3 20h18m-9 0V7a3 3 0 0 0-3-3H8a3 3 0 0 0-3 3v13");
}

</style>
