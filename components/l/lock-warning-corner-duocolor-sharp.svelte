<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="phl1oub2d"/><path class="sniojv7el"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-warning-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.phl1oub2d) {
  stroke-opacity: 0.4;
  d: path("M18 15v3m0 3h.01");
}

:global(.sniojv7el) {
  d: path("M11 21H4V9h16v2M8 9V7a4 4 0 1 1 8 0v2");
}

</style>
