<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yavtvzzuj"/><path class="r-6ivrbso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rocket-plus" {...props}></Icon>
<style>
:global(.r-6ivrbso) {
  d: path("M7.5 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yavtvzzuj) {
  d: path("M12.173 16H5.25v-6q0-4.5 3.75-7.5q3.75 3 3.75 7.5v5.177M5.25 10.5L2.75 13v2l2.5-1m7.5-3.5l2.475 2.475m-.035 2.001L12.75 14");
}

</style>
