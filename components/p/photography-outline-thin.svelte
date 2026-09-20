<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lts0lwvni"/><path class="ohwuksb6c"/><path class="cvere-4lf"/><path class="atq4odb0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:photography-outline-thin" {...props}></Icon>
<style>
:global(.atq4odb0h) {
  d: path("M11 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cvere-4lf) {
  d: path("m8 15 3 -3 3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lts0lwvni) {
  d: path("M5 6v13h13V6Z");
}

:global(.ohwuksb6c) {
  d: path("M8 3h13v13");
}

</style>
