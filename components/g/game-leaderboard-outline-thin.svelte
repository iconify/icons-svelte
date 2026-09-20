<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z5hkg0_kc"/><path class="xioi8tbab"/><path class="klx4022eb"/><path class="bih55pzif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-leaderboard-outline-thin" {...props}></Icon>
<style>
:global(.bih55pzif) {
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.klx4022eb) {
  d: path("M21 21v-7h-6");
}

:global(.xioi8tbab) {
  d: path("M3 21V11h6");
}

:global(.z5hkg0_kc) {
  d: path("M9 21V6h6v15Z");
}

</style>
