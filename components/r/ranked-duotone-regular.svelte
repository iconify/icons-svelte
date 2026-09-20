<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u96j_1b8m"/><path class="c2nlsybqj"/><path class="xtvmpefkx"/><path class="hclo6jb2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ranked-duotone-regular" {...props}></Icon>
<style>
:global(.c2nlsybqj) {
  d: path("M12 3s4 2 8 3v6c0 5 -4 8 -8 9 -4 -1 -8 -4 -8 -9V6c4 -1 8 -3 8 -3");
}

:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u96j_1b8m) {
  fill: currentColor;
  d: path("M12 3s4 2 8 3v6c0 5 -4 8 -8 9 -4 -1 -8 -4 -8 -9V6c4 -1 8 -3 8 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xtvmpefkx) {
  d: path("m8 13 4 -4 4 4");
}

</style>
