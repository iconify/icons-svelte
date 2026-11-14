<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7ifv_l9p"/><path class="g-dkdbc1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-bowl" {...props}></Icon>
<style>
:global(.g-dkdbc1m) {
  d: path("m9.5 18.25l-1 3.25h7l-1-3.25M8.5 13c-1.75-3-.25-5.5 1.5-7c0 2 1 3 2.25 3.25C11.5 6.5 12.5 4 15 2.5c-.25 3 2.75 6 .75 10.5");
}

:global(.t7ifv_l9p) {
  d: path("M3.5 13h17a8.5 5.5 0 0 1-17 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
