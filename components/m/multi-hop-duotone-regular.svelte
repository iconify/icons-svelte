<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i_bfpevyh"/><path class="rencte-ct"/><path class="i8wcjxb1o"/><path class="gnm51qbez"/><path class="fwlklcbzc"/><path class="zjs6ad-6z"/><path class="tdux9oy4s"/><path class="iwpbli9gm"/><path class="h57xi_b4m"/><path class="et81l2oxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multi-hop-duotone-regular" {...props}></Icon>
<style>
:global(.et81l2oxt) {
  d: path("M12 14a4 4 0 0 1 8 0");
}

:global(.fwlklcbzc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 14a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gnm51qbez) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 14a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h57xi_b4m) {
  d: path("M4 14a4 4 0 0 1 8 0");
}

:global(.i_bfpevyh) {
  fill: currentColor;
  d: path("M2 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.i8wcjxb1o) {
  fill: currentColor;
  d: path("M18 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iwpbli9gm) {
  d: path("M18 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rencte-ct) {
  fill: currentColor;
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tdux9oy4s) {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zjs6ad-6z) {
  d: path("M2 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
