<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtf0w138e"/><path class="a5tuk3h7e"/><path class="scwel3iok"/><path class="akar2ebka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drum-outline-thin" {...props}></Icon>
<style>
:global(.a5tuk3h7e) {
  d: path("M4 10h16");
}

:global(.akar2ebka) {
  d: path("m18 8 -4 -4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.scwel3iok) {
  d: path("m6 8 4 -4");
}

:global(.xtf0w138e) {
  d: path("M4 10v7h16v-7");
}

</style>
