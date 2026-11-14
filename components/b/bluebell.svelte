<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcqb0nbbi"/><path class="ox_bntbgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bluebell" {...props}></Icon>
<style>
:global(.hcqb0nbbi) {
  d: path("M4 21.5C4 12 6.5 4 12.5 4C16 4 18 5.5 18 8m-8-3.5v4");
}

:global(.ox_bntbgh) {
  d: path("M18 8c-2 0-2 1.5-2 3.5l-.5 2h5l-.5-2c0-2 0-3.5-2-3.5Zm-8 .5C8 8.5 8 10 8 12l-.5 2h5l-.5-2c0-2 0-3.5-2-3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
