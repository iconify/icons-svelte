<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjb6iab1i"/><path class="xkw-kioym"/><path class="hd0bezdcu"/><path class="f7kl6pbji"/><path class="ftqzjnb8u"/><path class="u649he-6w"/><path class="f-x5yl3mg"/><path class="vsmfi0bcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:intrusion-duotone-regular" {...props}></Icon>
<style>
:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.f7kl6pbji) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.hd0bezdcu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rjb6iab1i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u649he-6w) {
  d: path("M18 3v18");
}

:global(.vsmfi0bcq) {
  d: path("m10 9 3 3 -3 3");
}

:global(.xkw-kioym) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
