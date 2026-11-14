<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rvrkq1hgi"/><path class="l-m0pyb9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eco-dishwasher" {...props}></Icon>
<style>
:global(.l-m0pyb9j) {
  d: path("M7 13.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm8 7.75c0-5 2-7 6.5-7c0 4.5-2 7-6.5 7Zm0 0l3.5-3.5");
}

:global(.rvrkq1hgi) {
  d: path("M11.1 21.5H4v-19h16v9.3M4 7h16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
