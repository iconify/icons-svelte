<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sba68ybds"/><path class="nqutypyjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heading-6" {...props}></Icon>
<style>
:global(.nqutypyjj) {
  d: path("M15.25 16.25v-2.5c0-3 1.25-4.75 3.25-4.75c.75 0 1.25.25 1.75.75");
}

:global(.sba68ybds) {
  d: path("M3.5 5v14m8-14v14m-8-7h8m3.75 4.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
