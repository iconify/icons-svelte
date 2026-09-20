<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xx1tg77aj"/><path class="sr_2gtezx"/><path class="z5hkg0_kc"/><path class="xioi8tbab"/><path class="klx4022eb"/><path class="bih55pzif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-leaderboard-duotone-regular" {...props}></Icon>
<style>
:global(.bih55pzif) {
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.klx4022eb) {
  d: path("M21 21v-7h-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sr_2gtezx) {
  fill: currentColor;
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xioi8tbab) {
  d: path("M3 21V11h6");
}

:global(.xx1tg77aj) {
  fill: currentColor;
  d: path("M9 21V6h6v15Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z5hkg0_kc) {
  d: path("M9 21V6h6v15Z");
}

</style>
