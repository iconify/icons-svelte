<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rkhcfx2ju"/><path class="x2s10abgt"/><path class="festcnvxk"/><path class="bx3fv3b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:optimiser-duotone-thin" {...props}></Icon>
<style>
:global(.bx3fv3b8c) {
  d: path("M12 13v4");
}

:global(.festcnvxk) {
  d: path("m3 7 6 6h6l6 -6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rkhcfx2ju) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 7 6 6h6l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x2s10abgt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
