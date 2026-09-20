<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="iailgub_r"/><path class="yfojv1hdg"/><path class="bwm_5ejgf"/><path class="f4tjxs_8p"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r7dke9bth"/><path class="w8gxvdb9g"/><path class="c2hjexb6t"/><path class="nne1mobhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-bar-stacked-duotone-regular" {...props}></Icon>
<style>
:global(.bwm_5ejgf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c2hjexb6t) {
  d: path("M4 14h5");
}

:global(.f4tjxs_8p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iailgub_r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nne1mobhl) {
  d: path("M12 14h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.r7dke9bth) {
  d: path("M4 8h7");
}

:global(.w8gxvdb9g) {
  d: path("M14 8h5");
}

:global(.yfojv1hdg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
