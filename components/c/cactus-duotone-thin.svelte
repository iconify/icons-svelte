<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m3715abai"/><path class="q3dgvqbzs"/><path class="wcoay0fmb"/><path class="ri0jcjret"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cactus-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m3715abai) {
  fill: currentColor;
  d: path("M9 21V5h6v16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q3dgvqbzs) {
  d: path("M9 21V5h6v16Z");
}

:global(.ri0jcjret) {
  d: path("M15 15h4v-5");
}

:global(.wcoay0fmb) {
  d: path("M9 12H5V8");
}

</style>
