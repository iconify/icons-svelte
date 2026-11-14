<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="il6glvw9t"/><path class="qk_ynqbms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cave-survey" {...props}></Icon>
<style>
:global(.il6glvw9t) {
  d: path("M3 20.5V12a9 9 0 0 1 18 0v8.5");
}

:global(.qk_ynqbms) {
  d: path("m6.5 20l3.5-6.5l4 4l3-7m-7 3h.01m3.99 4h.01m2.99-7h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
