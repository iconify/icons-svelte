<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h7-t2qbtf"/><path class="cc9-_0c2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-plus-corner-duocolor" {...props}></Icon>
<style>
:global(.cc9-_0c2g) {
  d: path("M11 19H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4M4 6l4 4c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l4-4");
}

:global(.h7-t2qbtf) {
  stroke-opacity: 0.4;
  d: path("M15 18h6m-3-3v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
