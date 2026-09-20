<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gosl5tbza"/><path class="trzt6ibtx"/><path class="yitei-bhk"/><path class="qdn88l2uv"/><path class="g4h6r4ykz"/><path class="h3z-uye4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-up-from-line-duotone-regular" {...props}></Icon>
<style>
:global(.g4h6r4ykz) {
  d: path("M12 4v12");
}

:global(.gosl5tbza) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h3z-uye4u) {
  d: path("m8 8 4 -4 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qdn88l2uv) {
  d: path("M7 20h10");
}

:global(.trzt6ibtx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yitei-bhk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
