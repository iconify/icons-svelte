<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="opcwam8gv"/><path class="admnv1bfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-1-duocolor-round" {...props}></Icon>
<style>
:global(.admnv1bfe) {
  d: path("M3 20h18M9 20v-5.078a4 4 0 0 1 1.501-3.123l1-.8a4 4 0 0 1 4.998 0l1 .8A4 4 0 0 1 19 14.923V20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.opcwam8gv) {
  stroke-opacity: 0.4;
  d: path("M12 10.6V4H9a4 4 0 0 0-4 4v12");
}

</style>
