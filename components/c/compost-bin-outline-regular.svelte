<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rw4xuxb2g"/><path class="vn6-di86m"/><path class="cfeplwbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compost-bin-outline-regular" {...props}></Icon>
<style>
:global(.cfeplwbzd) {
  d: path("M12 17c-3 0 -4 -2 -4 -4 3 0 4 2 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rw4xuxb2g) {
  d: path("M6 10v10h12V10Z");
}

:global(.vn6-di86m) {
  d: path("M4 7h16");
}

</style>
