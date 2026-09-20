<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s6acipejh"/><path class="r8erdi8gm"/><path class="xw9luzbcb"/><path class="m28ld6blo"/><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="xtovmhbxk"/><path class="codat6b9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lane-change-duotone-regular" {...props}></Icon>
<style>
:global(.codat6b9f) {
  d: path("M11.5 6H15v3.5");
}

:global(.lwdt7zb5f) {
  d: path("M4 2v20");
}

:global(.m28ld6blo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.5 6H15v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pk1ekjvnl) {
  d: path("M20 2v20");
}

:global(.r8erdi8gm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s6acipejh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xtovmhbxk) {
  d: path("M9 19v-7l6 -6");
}

:global(.xw9luzbcb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 19v-7l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
