<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hlgqjd29s"/><path class="xy52n6bdp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-return-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.hlgqjd29s) {
  stroke-opacity: 0.4;
  d: path("M21 13v4h-8m3-3l-3 3l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xy52n6bdp) {
  d: path("M21 9V5H3v14h6M3 9h18");
}

</style>
