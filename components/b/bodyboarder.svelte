<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zjgcg4_4l"/><path class="lled2bb2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bodyboarder" {...props}></Icon>
<style>
:global(.lled2bb2c) {
  d: path("M9.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zjgcg4_4l) {
  d: path("M2.5 18H9c6 0 10.5-3 11-8c.25-4-3.5-5.5-5.25-3.25M3 15.25h9.5m-9-3l6-1.75");
}

</style>
