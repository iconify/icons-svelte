<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ryo9062lk"/><path class="anx8jnbhv"/><path class="v2mnclz8q"/><path class="etsafvbhb"/><path class="dazmnqbya"/><path class="emo-jf0pj"/><path class="d_b1a31kv"/><path class="sbr7qlk2q"/><path class="kfx9jcc5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deepfake-detect-duotone-regular" {...props}></Icon>
<style>
:global(.anx8jnbhv) {
  fill: currentColor;
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d_b1a31kv) {
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.dazmnqbya) {
  d: path("M3 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.emo-jf0pj) {
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.etsafvbhb) {
  fill: currentColor;
  d: path("M12.5 16.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kfx9jcc5b) {
  d: path("m19.5 19.5 2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ryo9062lk) {
  fill: currentColor;
  d: path("M3 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sbr7qlk2q) {
  d: path("M12.5 16.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.v2mnclz8q) {
  fill: currentColor;
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
