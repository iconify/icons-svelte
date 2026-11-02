<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mb86pob5t"/><path class="ztrhk2p1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-duocolor-sharp" {...props}></Icon>
<style>
:global(.mb86pob5t) {
  stroke-opacity: 0.4;
  d: path("m3 5l6 6h6l6-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ztrhk2p1s) {
  d: path("M12 19H3V5h18v14z");
}

</style>
