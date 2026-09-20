<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aep_ellef"/><path class="q84dtjb2k"/><path class="wn08sczhn"/><path class="ag9lytb5i"/><path class="ftqzjnb8u"/><path class="u649he-6w"/><path class="f-x5yl3mg"/><path class="vsmfi0bcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:intrusion-duotone-bold" {...props}></Icon>
<style>
:global(.aep_ellef) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ag9lytb5i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.q84dtjb2k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u649he-6w) {
  d: path("M18 3v18");
}

:global(.vsmfi0bcq) {
  d: path("m10 9 3 3 -3 3");
}

:global(.wn08sczhn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
