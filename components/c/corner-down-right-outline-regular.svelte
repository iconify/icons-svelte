<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="isvgtub8p"/><path class="xpi-ctm3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-down-right-outline-regular" {...props}></Icon>
<style>
:global(.isvgtub8p) {
  d: path("M4 4v10h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xpi-ctm3k) {
  d: path("m15 9 5 5 -5 5");
}

</style>
