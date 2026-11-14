<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aof9_hbic"/><path class="xk03ohb9g"/><path class="y3honzxlq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:quote-open" {...props}></Icon>
<style>
:global(.aof9_hbic) {
  d: path("M3.75 15.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xk03ohb9g) {
  d: path("M3.75 15.5c0-4.5 2-7.5 5.75-9m4.25 9a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.y3honzxlq) {
  d: path("M13.75 15.5c0-4.5 2-7.5 5.75-9");
}

</style>
