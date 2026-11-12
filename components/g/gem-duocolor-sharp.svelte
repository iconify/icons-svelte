<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h5nl8ib0a"/><path class="anozd_bhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gem-duocolor-sharp" {...props}></Icon>
<style>
:global(.anozd_bhu) {
  d: path("M7 5h10l4 4l-9 10L3 9z");
}

:global(.h5nl8ib0a) {
  stroke-opacity: 0.4;
  d: path("m8 9l2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
