<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="ojq1jdsdp"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="o0-p394ku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rate-of-change-duotone-regular" {...props}></Icon>
<style>
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

:global(.o0-p394ku) {
  d: path("M7 17h5l4 -4V7");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.ojq1jdsdp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 17h5l4 -4V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

</style>
