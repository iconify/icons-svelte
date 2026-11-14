<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hj60lablu"/><path class="xez9qwptf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eye-wink" {...props}></Icon>
<style>
:global(.hj60lablu) {
  d: path("M2.5 12C3.75 9.5 5 8 6.75 8s3 1.5 4.25 4c-1.25 2.5-2.5 4-4.25 4s-3-1.5-4.25-4Zm11.25-1q4 5.5 7.75 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xez9qwptf) {
  d: path("M5.5 12A1.25 1.25 0 1 0 8 12a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
