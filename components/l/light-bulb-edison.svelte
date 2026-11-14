<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_rnd6boi"/><path class="b-c5l68al"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:light-bulb-edison" {...props}></Icon>
<style>
:global(.b-c5l68al) {
  d: path("M10.25 11.75V10.5a1.75 1.75 0 0 1 3.5 0v1.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_rnd6boi) {
  d: path("M9.25 16v-1C7 13.75 5.5 11.75 5.5 9.25a6.5 6.5 0 0 1 13 0c0 2.5-1.5 4.5-3.75 5.75v1Zm0 2.75h5.5M10.5 21.5h3");
}

</style>
