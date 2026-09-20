<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gmozx1btc"/><path class="o8p9igehf"/><path class="lkivjibuo"/><path class="qdn88l2uv"/><path class="bdehoybwy"/><path class="bx6cs-b9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:personal-best-duotone-regular" {...props}></Icon>
<style>
:global(.bdehoybwy) {
  d: path("M8 8.5a2.5 2.5 0 0 1 0 -5");
}

:global(.bx6cs-b9q) {
  d: path("M16 3.5a2.5 2.5 0 0 1 0 5");
}

:global(.gmozx1btc) {
  fill: currentColor;
  d: path("M8 3h8v6l-4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lkivjibuo) {
  d: path("M12 13v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8p9igehf) {
  d: path("M8 3h8v6l-4 4 -4 -4Z");
}

:global(.qdn88l2uv) {
  d: path("M7 20h10");
}

</style>
