<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byrw8520t"/><path class="hc4jj6btd"/><path class="h4kqfjbnm"/><path class="aotnjcbls"/><path class="gmngh8b8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blood-sugar-duotone-thin" {...props}></Icon>
<style>
:global(.aotnjcbls) {
  d: path("M4 13h7");
}

:global(.byrw8520t) {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gmngh8b8n) {
  d: path("m18 5 3.5 3.5a3.5 3.5 0 1 1 -7 0Z");
}

:global(.h4kqfjbnm) {
  d: path("M2 9a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.hc4jj6btd) {
  fill: currentColor;
  d: path("m18 5 3.5 3.5a3.5 3.5 0 1 1 -7 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
