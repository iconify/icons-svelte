<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zitzxjbtk"/><path class="ypogw4bqt"/><path class="r5o-d4b5v"/><path class="mhila7bcl"/><path class="jka0cfj-k"/><path class="egsaq3b2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-right-to-line-duotone-thin" {...props}></Icon>
<style>
:global(.egsaq3b2f) {
  d: path("m12 8 4 4 -4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jka0cfj-k) {
  d: path("M4 12h12");
}

:global(.mhila7bcl) {
  d: path("M20 7v10");
}

:global(.r5o-d4b5v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ypogw4bqt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zitzxjbtk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
