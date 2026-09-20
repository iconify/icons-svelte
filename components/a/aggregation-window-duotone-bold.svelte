<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="e3qtgdcij"/><path class="d5nul9dav"/><path class="l_hx63kbe"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="kswphkyfs"/><path class="rgj9t7gfi"/><path class="g45hqpb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aggregation-window-duotone-bold" {...props}></Icon>
<style>
:global(.d5nul9dav) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 7H16v10h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e3qtgdcij) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 7H8v10h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g45hqpb0s) {
  d: path("M10.5 12h3");
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kswphkyfs) {
  d: path("M10.5 7H8v10h2.5");
}

:global(.l_hx63kbe) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.rgj9t7gfi) {
  d: path("M13.5 7H16v10h-2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
