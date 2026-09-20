<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y5f6c-4ni"/><path class="s-6rb6b-a"/><path class="n8sqmebht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pet-bowl-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n8sqmebht) {
  d: path("M7 18h10");
}

:global(.s-6rb6b-a) {
  d: path("M4 8h16c0 4 -3 7 -8 7s-8 -3 -8 -7");
}

:global(.y5f6c-4ni) {
  fill: currentColor;
  d: path("M4 8h16c0 4 -3 7 -8 7s-8 -3 -8 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
