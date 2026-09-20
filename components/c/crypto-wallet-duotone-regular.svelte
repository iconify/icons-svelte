<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ycx5d_b4j"/><path class="cnjf-ebwx"/><path class="ex6sma95g"/><path class="b6gnpqbjb"/><path class="nzb-j6sxx"/><path class="rnyye8dag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crypto-wallet-duotone-regular" {...props}></Icon>
<style>
:global(.b6gnpqbjb) {
  d: path("M10 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cnjf-ebwx) {
  fill: currentColor;
  d: path("M10 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ex6sma95g) {
  d: path("M8 3h8l5 5v8l-5 5H8l-5 -5V8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzb-j6sxx) {
  d: path("M12 12.5V15");
}

:global(.rnyye8dag) {
  d: path("M12 13.5h2.5");
}

:global(.ycx5d_b4j) {
  fill: currentColor;
  d: path("M8 3h8l5 5v8l-5 5H8l-5 -5V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
