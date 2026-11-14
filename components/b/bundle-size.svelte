<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j-_57tbrl"/><path class="vvjh53a6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bundle-size" {...props}></Icon>
<style>
:global(.j-_57tbrl) {
  d: path("m12 2.5l8 4V14l-8 4l-8-4V6.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vvjh53a6m) {
  d: path("m4 6.5l8 4l8-4m-8 4V18m-8 3h16M4 19.5V22m16-2.5V22");
}

</style>
