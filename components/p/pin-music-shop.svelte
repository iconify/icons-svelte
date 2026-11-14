<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nry97wv9n"/><path class="fugfefasg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-music-shop" {...props}></Icon>
<style>
:global(.fugfefasg) {
  d: path("M6.25 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.nry97wv9n) {
  d: path("M9 11a5 5 0 1 0 4 4a3.5 3.5 0 1 0-4-4Zm6-2l3.25-3.25m2.03-4.152l2.122 2.122l-3.182 3.182l-2.122-2.122Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
