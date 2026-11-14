<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nipuh34zy"/><path class="e18i-wb_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:door-flush" {...props}></Icon>
<style>
:global(.e18i-wb_a) {
  d: path("M15.25 10.75v1.5h-3");
}

:global(.nipuh34zy) {
  d: path("M5.5 2.5h13v19h-13ZM3 21.5h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
