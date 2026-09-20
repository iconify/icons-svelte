<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="bvowdpkby"/><path class="bjr-m2bij"/><path class="ke9b-u_dj"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="kswphkyfs"/><path class="rgj9t7gfi"/><path class="g45hqpb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aggregation-window-duotone-thin" {...props}></Icon>
<style>
:global(.bjr-m2bij) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 7H16v10h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bvowdpkby) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 7H8v10h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g45hqpb0s) {
  d: path("M10.5 12h3");
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ke9b-u_dj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kswphkyfs) {
  d: path("M10.5 7H8v10h2.5");
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

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
