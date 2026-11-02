<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yagfc6xce"/><path class="uaw488bdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:backspace-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uaw488bdq) {
  d: path("M15 6h4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H9l-5-5a1.414 1.414 0 0 1 0-2l5-5z");
}

:global(.yagfc6xce) {
  stroke-opacity: 0.4;
  d: path("m13 10l4 4m0-4l-4 4");
}

</style>
