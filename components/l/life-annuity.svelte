<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xu3nmbclo"/><path class="sf1ijidwf"/><path class="oj0aovi6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:life-annuity" {...props}></Icon>
<style>
:global(.oj0aovi6j) {
  d: path("M8.25 9v6a3.75 1.75 0 0 0 7.5 0V9m-7.5 3a3.75 1.75 0 0 0 7.5 0");
}

:global(.sf1ijidwf) {
  d: path("M5 3.25L7.5 4l-.75 2.5M8.25 9a3.75 1.75 0 1 0 7.5 0a3.75 1.75 0 1 0-7.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xu3nmbclo) {
  d: path("M16.5 4a9.25 9.25 0 1 1-9 0");
}

</style>
