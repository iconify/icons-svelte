<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zrgzrac8b"/><path class="b1assqlxb"/><path class="j7tyb2zrz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:location-precise" {...props}></Icon>
<style>
:global(.b1assqlxb) {
  d: path("M8.25 9.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

:global(.j7tyb2zrz) {
  fill: currentColor;
  d: path("M11 9.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zrgzrac8b) {
  d: path("M12 21.5c-4-4.5-7-8-7-12a7 7 0 0 1 14 0c0 4-3 7.5-7 12Z");
}

</style>
