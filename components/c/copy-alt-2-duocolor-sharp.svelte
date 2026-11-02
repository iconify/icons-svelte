<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dg1uuk8rq"/><path class="n70g8xb1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-alt-2-duocolor-sharp" {...props}></Icon>
<style>
:global(.dg1uuk8rq) {
  stroke-opacity: 0.4;
  d: path("M9 5V3h12v12h-2");
}

:global(.n70g8xb1k) {
  d: path("M3 9h12v12H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
