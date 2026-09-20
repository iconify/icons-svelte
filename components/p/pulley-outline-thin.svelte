<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="se8tg3byo"/><path class="ayfng4o1h"/><path class="pg4kk0y8v"/><path class="sy7mvubrh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pulley-outline-thin" {...props}></Icon>
<style>
:global(.ayfng4o1h) {
  d: path("M5 6v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pg4kk0y8v) {
  d: path("M13 6v7");
}

:global(.se8tg3byo) {
  d: path("M5 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.sy7mvubrh) {
  d: path("M9 13h8v6H9Z");
}

</style>
