<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3emery0c"/><path class="tethvackr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-check-duocolor" {...props}></Icon>
<style>
:global(.n3emery0c) {
  stroke-opacity: 0.4;
  d: path("m9 11l2 2l4-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tethvackr) {
  d: path("M12 17H6a2 2 0 0 1-2-2c0-1 1-1 1-2v-3a7 7 0 0 1 14 0v3c0 1 1 1 1 2a2 2 0 0 1-2 2zm-3 0v1a3 3 0 0 0 6 0v-1");
}

</style>
