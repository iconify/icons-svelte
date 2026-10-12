<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uui-leb4t"/><path class="lj2ej1xdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:package-off" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lj2ej1xdl) {
  d: path("m4 7.25l8 4l8-4m-8 4v9M7.75 4.75L16 9.25");
}

:global(.uui-leb4t) {
  d: path("M20.25 7.65v8.7a1.5 1.5 0 0 1-.8 1.3l-6.55 3.4a2 2 0 0 1-1.8 0l-6.55-3.4a1.5 1.5 0 0 1-.8-1.3v-8.7a1.5 1.5 0 0 1 .8-1.3l6.55-3.4a2 2 0 0 1 1.8 0l6.55 3.4a1.5 1.5 0 0 1 .8 1.3");
}

</style>
