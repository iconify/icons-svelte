<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="djh6i29cv"/><path class="yj5kz583k"/><path class="shadeon3y"/><path class="bjl79lrrh"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="el687jbox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:goal-trigger-duotone-regular" {...props}></Icon>
<style>
:global(.bjl79lrrh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 6 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.djh6i29cv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.el687jbox) {
  d: path("m15 6 -3 3h2.5l-3 3");
}

:global(.hspeesv2z) {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.shadeon3y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.5 20.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tv6hbrcra) {
  d: path("M8.5 20.5h7");
}

:global(.ujt25lh2u) {
  d: path("M12 15v5.5");
}

:global(.yj5kz583k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 15v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
