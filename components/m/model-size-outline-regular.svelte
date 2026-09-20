<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i3nsbzblu"/><path class="rg7tj2b_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-size-outline-regular" {...props}></Icon>
<style>
:global(.i3nsbzblu) {
  d: path("m10 3 7 7 -7 7 -7 -7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rg7tj2b_x) {
  d: path("m18 14 3.5 3.5L18 21l-3.5 -3.5Z");
}

</style>
