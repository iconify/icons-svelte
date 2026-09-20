<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qv06t9afb"/><path class="rbdg4rb5l"/><path class="e69i7fcek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kitchen-knife-duotone-thin" {...props}></Icon>
<style>
:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qv06t9afb) {
  fill: currentColor;
  d: path("M3 17h14V7h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rbdg4rb5l) {
  d: path("M3 17h14V7h-4Z");
}

</style>
