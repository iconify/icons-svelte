<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jianh4bcb"/><path class="noe97lr0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:concrete-mixer-truck" {...props}></Icon>
<style>
:global(.jianh4bcb) {
  d: path("M2.5 15.5h19v-4l-3-3.5h-3v7.5");
}

:global(.noe97lr0b) {
  d: path("M3.25 10.75a5 3.5-20 0 1 9.5-3.5a5 3.5-20 0 1-9.5 3.5ZM5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
