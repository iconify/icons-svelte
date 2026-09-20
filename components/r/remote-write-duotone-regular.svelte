<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="ug-yr5rhi"/><path class="prxtjqb7i"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="bw_to0b8d"/><path class="qd0z4jbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:remote-write-duotone-regular" {...props}></Icon>
<style>
:global(.bw_to0b8d) {
  d: path("M7 12h12");
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.prxtjqb7i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 9.5 19 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qd0z4jbov) {
  d: path("M16.5 9.5 19 12l-2.5 2.5");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.ug-yr5rhi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
