<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pr37be5vj"/><path class="gzjf714fp"/><path class="asoso3n9i"/><path class="qxfpuob8x"/><path class="fvteuwbda"/><path class="eegqg8bki"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="qhy91zm_e"/><path class="a9xckwbov"/><path class="qlfruhq7c"/><path class="br_h3vzli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-compress-duotone-regular" {...props}></Icon>
<style>
:global(.a9xckwbov) {
  d: path("m9 10 2 2 -2 2");
}

:global(.asoso3n9i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.eegqg8bki) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fvteuwbda) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gzjf714fp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pr37be5vj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qhy91zm_e) {
  d: path("M6 12h5");
}

:global(.qlfruhq7c) {
  d: path("M13 12h5");
}

:global(.qxfpuob8x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
