<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nib87abyv"/><path class="a7vpafiwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:box-label-outline-regular" {...props}></Icon>
<style>
:global(.a7vpafiwa) {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nib87abyv) {
  d: path("M4 8h12l4 4 -4 4H4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
