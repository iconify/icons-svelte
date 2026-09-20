<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tns1-ur3v"/><path class="nqbub38-r"/><path class="bcqk9b5zt"/><path class="bm-drdp9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:litter-pick-outline-thin" {...props}></Icon>
<style>
:global(.bcqk9b5zt) {
  d: path("m13 13 3 3");
}

:global(.bm-drdp9q) {
  d: path("M8 19h6v3H8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nqbub38-r) {
  d: path("m13 13 -3 3");
}

:global(.tns1-ur3v) {
  d: path("m4 4 9 9");
}

</style>
