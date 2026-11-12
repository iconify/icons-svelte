<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zgt00bc2e"/><path class="e4-xs6b1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-square-duocolor-sharp" {...props}></Icon>
<style>
:global(.e4-xs6b1o) {
  d: path("M3 3h4v4H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zgt00bc2e) {
  stroke-opacity: 0.4;
  d: path("m10 10l11 4l-5 2l-2 5z");
}

</style>
