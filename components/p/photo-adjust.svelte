<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e2d528bfk"/><path class="djkmikq9j"/><path class="zhl-6bcgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:photo-adjust" {...props}></Icon>
<style>
:global(.djkmikq9j) {
  d: path("M4.5 18.5L9 13l3.099 3.787M12.75 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm2 9.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.e2d528bfk) {
  d: path("M12 18.5H2.5v-15h18v9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zhl-6bcgv) {
  fill: currentColor;
  d: path("M18 14.75a3.25 3.25 0 0 1 0 6.5Z");
}

</style>
