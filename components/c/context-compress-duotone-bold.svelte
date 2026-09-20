<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x87wa6b5t"/><path class="lx3jyybfn"/><path class="skzikx2yi"/><path class="u_6_8ab4e"/><path class="r5u5lrb-w"/><path class="su_f3o4hp"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="qhy91zm_e"/><path class="a9xckwbov"/><path class="qlfruhq7c"/><path class="br_h3vzli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-compress-duotone-bold" {...props}></Icon>
<style>
:global(.a9xckwbov) {
  d: path("m9 10 2 2 -2 2");
}

:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.br_h3vzli) {
  d: path("m15 10 -2 2 2 2");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.lx3jyybfn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qhy91zm_e) {
  d: path("M6 12h5");
}

:global(.qlfruhq7c) {
  d: path("M13 12h5");
}

:global(.r5u5lrb-w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.skzikx2yi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.su_f3o4hp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u_6_8ab4e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x87wa6b5t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
