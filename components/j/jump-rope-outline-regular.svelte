<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eguxbnz0i"/><path class="a3zqh3bcj"/><path class="he6b77rju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jump-rope-outline-regular" {...props}></Icon>
<style>
:global(.a3zqh3bcj) {
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.eguxbnz0i) {
  d: path("M20 10a8 8 0 0 1 -16 0");
}

:global(.he6b77rju) {
  d: path("M18 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
