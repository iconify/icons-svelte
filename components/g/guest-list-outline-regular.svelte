<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z7wppxt9k"/><path class="ce80bno8x"/><path class="qvytntb8g"/><path class="c6uw-ccfl"/><path class="f8arnkt8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guest-list-outline-regular" {...props}></Icon>
<style>
:global(.c6uw-ccfl) {
  d: path("M7 14h10");
}

:global(.ce80bno8x) {
  d: path("M9 5V2h6v3");
}

:global(.f8arnkt8y) {
  d: path("M7 18h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvytntb8g) {
  d: path("M7 10h10");
}

:global(.z7wppxt9k) {
  d: path("M4 5v16h16V5Z");
}

</style>
