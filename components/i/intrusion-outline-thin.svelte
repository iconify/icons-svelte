<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftqzjnb8u"/><path class="u649he-6w"/><path class="f-x5yl3mg"/><path class="vsmfi0bcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:intrusion-outline-thin" {...props}></Icon>
<style>
:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u649he-6w) {
  d: path("M18 3v18");
}

:global(.vsmfi0bcq) {
  d: path("m10 9 3 3 -3 3");
}

</style>
