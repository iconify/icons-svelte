<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a9q1iwbbu"/><path class="a7a9ymcaq"/><path class="id4vqxf8c"/><path class="qlw91sbif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overfit-gap-duotone-regular" {...props}></Icon>
<style>
:global(.a7a9ymcaq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 19 5 -5h4l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.a9q1iwbbu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 14 5 -5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.id4vqxf8c) {
  d: path("m4 14 5 -5h11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qlw91sbif) {
  d: path("m4 19 5 -5h4l4 4");
}

</style>
