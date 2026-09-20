<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="jerxe9ocu"/><path class="hrevw_blx"/><path class="to528to2t"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="kswphkyfs"/><path class="rgj9t7gfi"/><path class="g45hqpb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aggregation-window-duotone-regular" {...props}></Icon>
<style>
:global(.g45hqpb0s) {
  d: path("M10.5 12h3");
}

:global(.hrevw_blx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 7H16v10h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jerxe9ocu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 7H8v10h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kswphkyfs) {
  d: path("M10.5 7H8v10h2.5");
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

:global(.rgj9t7gfi) {
  d: path("M13.5 7H16v10h-2.5");
}

:global(.to528to2t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
