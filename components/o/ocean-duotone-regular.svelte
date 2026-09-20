<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g-c585l0n"/><path class="sfn2vpdkc"/><path class="ran4xbbmm"/><path class="lmj_kj__f"/><path class="oy_r10b4z"/><path class="yzilgtbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ocean-duotone-regular" {...props}></Icon>
<style>
:global(.g-c585l0n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 8 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmj_kj__f) {
  d: path("m3 8 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oy_r10b4z) {
  d: path("m3 14 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.ran4xbbmm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 20 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sfn2vpdkc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 14 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yzilgtbzd) {
  d: path("m3 20 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
