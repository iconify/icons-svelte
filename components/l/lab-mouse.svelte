<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e4gk14b9q"/><path class="dou4n5biz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lab-mouse" {...props}></Icon>
<style>
:global(.dou4n5biz) {
  d: path("m6.5 6.5l3 2.5l-3 2.5m5 0h4");
}

:global(.e4gk14b9q) {
  d: path("M2.5 2.5h19v13h-19Zm2 16h15v3h-15Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
