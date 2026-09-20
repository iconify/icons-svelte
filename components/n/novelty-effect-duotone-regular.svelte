<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb7yzvvzz"/><path class="d0q7jt_zp"/><path class="qe97cg-lx"/><path class="sfefbpbuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:novelty-effect-duotone-regular" {...props}></Icon>
<style>
:global(.d0q7jt_zp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 15 5 -5 4 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gb7yzvvzz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.sfefbpbuh) {
  d: path("m5 15 5 -5 4 4h5");
}

</style>
