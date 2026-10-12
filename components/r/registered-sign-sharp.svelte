<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j61d72bmp"/><circle class="qdb17cczo"/><path class="ybj1st_9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:registered-sign-sharp" {...props}></Icon>
<style>
:global(.j61d72bmp) {
  d: path("M3 13h9m-9 5h12");
}

:global(.qdb17cczo) {
  cx: 17px;
  cy: 7px;
  r: 4.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybj1st_9r) {
  d: path("M16 8.6V5.4h2.35v2.2H16m1.25 0l.75 1");
}

</style>
