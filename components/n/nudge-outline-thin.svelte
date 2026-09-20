<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-m1aobza"/><path class="e0ead5bmw"/><path class="pf-zwj5ei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nudge-outline-thin" {...props}></Icon>
<style>
:global(.e0ead5bmw) {
  d: path("M3 12h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pf-zwj5ei) {
  d: path("m6 10 2 2 -2 2");
}

:global(.v-m1aobza) {
  d: path("M16.32 7a5.5 5.5 0 1 1 -4.64 0");
}

</style>
