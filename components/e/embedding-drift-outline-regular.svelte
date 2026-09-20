<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h1f2yzbjx"/><path class="srf482-ro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embedding-drift-outline-regular" {...props}></Icon>
<style>
:global(.h1f2yzbjx) {
  d: path("M8.5 5 11 7.5l-4 4 -4 -4L5.5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.srf482-ro) {
  d: path("m10 14 3 3 3 -3 3 3");
}

</style>
