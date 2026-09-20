<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ydpucsi6v"/><path class="bod4n0b3z"/><path class="ar9f68bct"/><path class="a5uqb5btg"/><path class="lzjw7bcdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ecosystem-outline-regular" {...props}></Icon>
<style>
:global(.a5uqb5btg) {
  d: path("M9 14v4");
}

:global(.ar9f68bct) {
  d: path("M6 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.lzjw7bcdy) {
  d: path("M14 18v-5h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ydpucsi6v) {
  d: path("M2 18a10 10 0 0 1 20 0");
}

</style>
