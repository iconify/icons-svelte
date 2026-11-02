<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hk0u4yb2t"/><path class="g3x--wjvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bed-duocolor" {...props}></Icon>
<style>
:global(.g3x--wjvo) {
  d: path("M3 5v14M3 9h16a2 2 0 0 1 2 2v8M3 16h18");
}

:global(.hk0u4yb2t) {
  stroke-opacity: 0.4;
  d: path("M7 9v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
