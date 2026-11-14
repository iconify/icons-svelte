<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ic8gymbdv"/><path class="z514gmasc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kiosk-news" {...props}></Icon>
<style>
:global(.ic8gymbdv) {
  d: path("m2.5 8.5l2.5-5h14l2.5 5Zm2 0v13h15v-13m-15 7h15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z514gmasc) {
  d: path("M8.5 11.25h7v4.25h-7Zm3.5 0v4.25");
}

</style>
