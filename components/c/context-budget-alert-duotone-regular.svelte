<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c07le3bhf"/><path class="pr37be5vj"/><path class="gzjf714fp"/><path class="ufppdlbpv"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="pfpu_3ppl"/><path class="y1lnycw3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-budget-alert-duotone-regular" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.c07le3bhf) {
  fill: currentColor;
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
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

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.pr37be5vj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ufppdlbpv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y1lnycw3l) {
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
