<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="now253bdc"/><path class="ietvg-b5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-foldable-duocolor-sharp" {...props}></Icon>
<style>
:global(.ietvg-b5k) {
  d: path("m3 5l7-2h4l7 2v14l-7 2h-4l-7-2zm3 2h.01");
}

:global(.now253bdc) {
  stroke-opacity: 0.4;
  d: path("M12 3v18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
