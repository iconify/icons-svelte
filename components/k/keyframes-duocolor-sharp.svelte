<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a-gb0nb6l"/><path class="u9nwozrcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:keyframes-duocolor-sharp" {...props}></Icon>
<style>
:global(.a-gb0nb6l) {
  stroke-opacity: 0.4;
  d: path("m5 9l-3 3l3 3m14-6l3 3l-3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u9nwozrcu) {
  d: path("m14 10l2 2l-4 4l-4-4l4-4z");
}

</style>
