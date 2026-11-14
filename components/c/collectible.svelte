<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7lktrbfb"/><path class="bh-5wrbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:collectible" {...props}></Icon>
<style>
:global(.bh-5wrbyl) {
  d: path("M6 13.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM18.75 2.5q0 2.75 2.75 2.75q-2.75 0-2.75 2.75q0-2.75-2.75-2.75q2.75 0 2.75-2.75Z");
}

:global(.t7lktrbfb) {
  d: path("M2.75 13.75a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
