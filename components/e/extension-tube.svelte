<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wt98u8b5m"/><path class="vfhyzoiuw"/><path class="fmabdia2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:extension-tube" {...props}></Icon>
<style>
:global(.fmabdia2m) {
  d: path("M11 3.5a4 8.5 0 0 1 0 17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vfhyzoiuw) {
  d: path("M6.5 3.5h11a4 8.5 0 0 1 0 17h-11");
}

:global(.wt98u8b5m) {
  d: path("M2.5 12a4 8.5 0 1 0 8 0a4 8.5 0 1 0-8 0Z");
}

</style>
