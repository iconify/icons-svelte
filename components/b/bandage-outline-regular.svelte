<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tkahp9b1r"/><path class="vokybza2s"/><path class="xbdh32u_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bandage-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tkahp9b1r) {
  d: path("M3 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.vokybza2s) {
  d: path("M7 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.xbdh32u_w) {
  d: path("M17 12h4v7");
}

</style>
