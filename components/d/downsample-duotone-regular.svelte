<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="sgkysfjiu"/><path class="aezb-8gtu"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="d2jiu7bqo"/><path class="gzqe0db9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:downsample-duotone-regular" {...props}></Icon>
<style>
:global(.aezb-8gtu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d2jiu7bqo) {
  d: path("m7 15 2 -2 2 2 2 -2");
}

:global(.gzqe0db9p) {
  d: path("m15 15 4 -4");
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

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.sgkysfjiu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 15 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
