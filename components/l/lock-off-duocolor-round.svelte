<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dytifdcql"/><path class="lxakf52su"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-off-duocolor-round" {...props}></Icon>
<style>
:global(.dytifdcql) {
  stroke-opacity: 0.4;
  d: path("M9 6a3 3 0 0 1 6 0v4M2 5l17 17");
}

:global(.lxakf52su) {
  d: path("M17.647 20.647A4 4 0 0 1 16 21H8a4 4 0 0 1-4-4v-3c0-1.9 1.325-3.49 3.101-3.899M13 10h3a4 4 0 0 1 4 4v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
