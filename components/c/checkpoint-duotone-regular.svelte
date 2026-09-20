<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjb6iab1i"/><path class="qhtl8ilhw"/><path class="ftqzjnb8u"/><path class="qnhyftzmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-duotone-regular" {...props}></Icon>
<style>
:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qhtl8ilhw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 5h12v7H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnhyftzmc) {
  d: path("M6 5h12v7H6");
}

:global(.rjb6iab1i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
