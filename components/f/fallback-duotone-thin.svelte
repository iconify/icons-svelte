<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pgcyabcdk"/><path class="v_45uabpq"/><path class="sbiy6014w"/><path class="c46fyy1pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fallback-duotone-thin" {...props}></Icon>
<style>
:global(.c46fyy1pe) {
  d: path("m16 12 3 3 -3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pgcyabcdk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h9v8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sbiy6014w) {
  d: path("M3 7h9v8h7");
}

:global(.v_45uabpq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 12 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
