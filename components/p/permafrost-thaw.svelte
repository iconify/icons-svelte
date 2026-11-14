<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwkp65gco"/><path class="sagdefoiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:permafrost-thaw" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pwkp65gco) {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 6 3");
}

:global(.sagdefoiz) {
  d: path("m2.5 7l3.25 3L9 7l3 3l3-3l3.25 3l3.25-3M12 12.75c.75 1 2.25 2.25 2.25 3.25a2.25 2.25 0 0 1-4.5 0c0-1 1.5-2.25 2.25-3.25");
}

</style>
