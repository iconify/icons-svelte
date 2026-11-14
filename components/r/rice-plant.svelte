<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y7okrmbcz"/><path class="hy_jd70na"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rice-plant" {...props}></Icon>
<style>
:global(.hy_jd70na) {
  d: path("M17 10.25a1.75 3.5 0 1 0 3.5 0a1.75 3.5 0 1 0-3.5 0ZM8 21.5c-1.5-3-3.5-4.5-5.5-5m6-1.5c1.5-1.75 3.5-2.25 6-1.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y7okrmbcz) {
  d: path("M8 21.5C8 13 11 5.5 16 4c1.5-.5 2.5.5 2.75 2.75");
}

</style>
