<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vjbwu0pwl"/><path class="bi1pcx29v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crop-monitor" {...props}></Icon>
<style>
:global(.bi1pcx29v) {
  d: path("M12 11c0-1.68-1.12-2.57-3-2.5c.07 1.5 1.2 2.4 3 2.5Zm0-1c0-1.8 1.13-3.15 3-3.25c-.07 1.9-1.2 3.25-3 3.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vjbwu0pwl) {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8m-4-7.25V10");
}

</style>
