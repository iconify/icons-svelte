<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="shhtmacsp"/><path class="y7n4sgyet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-check-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.shhtmacsp) {
  stroke-opacity: 0.4;
  d: path("m9 14l2 2l4-4");
}

:global(.y7n4sgyet) {
  d: path("M9 5H5v16h14V5h-4M9 5V3h6v2M9 5v2h6V5");
}

</style>
