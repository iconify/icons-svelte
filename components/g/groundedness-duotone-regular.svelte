<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m9uyd-z1l"/><path class="u5jltjbuw"/><path class="duxy6wbvl"/><path class="ok9ioqb8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:groundedness-duotone-regular" {...props}></Icon>
<style>
:global(.duxy6wbvl) {
  d: path("m7 9 4 4 6 -6");
}

:global(.m9uyd-z1l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 9 4 4 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.u5jltjbuw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
