<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dhm9wy0nm"/><path class="o8scmcc3i"/><path class="uxy9sxbfx"/><path class="o50_pabww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:best-of-n-outline-regular" {...props}></Icon>
<style>
:global(.dhm9wy0nm) {
  d: path("M3 5h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o50_pabww) {
  d: path("m16 12 2 2 4 -4");
}

:global(.o8scmcc3i) {
  d: path("M3 12h10");
}

:global(.uxy9sxbfx) {
  d: path("M3 19h10");
}

</style>
