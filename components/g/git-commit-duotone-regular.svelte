<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lsj8eccpk"/><path class="cajt03bfr"/><path class="cktduhxcf"/><path class="el3g3frja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-commit-duotone-regular" {...props}></Icon>
<style>
:global(.cajt03bfr) {
  d: path("m4 20 5 -5");
}

:global(.cktduhxcf) {
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

:global(.el3g3frja) {
  d: path("m15 9 5 -5");
}

:global(.lsj8eccpk) {
  fill: currentColor;
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
