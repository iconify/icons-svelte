<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m0qnqtbtv"/><path class="i0felcflz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dac-audio" {...props}></Icon>
<style>
:global(.i0felcflz) {
  d: path("M9 12q1.5-3.75 3 0t3 0");
}

:global(.m0qnqtbtv) {
  d: path("M5.5 5.5h13v13h-13Zm-3 3h3m-3 3.5h3m-3 3.5h3m13-7h3m-3 3.5h3m-3 3.5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
