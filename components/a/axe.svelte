<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qcgfb0dhz"/><path class="gibbinwgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:axe" {...props}></Icon>
<style>
:global(.gibbinwgp) {
  d: path("M16.25 6.25L14 2.75q-3.75.5-4.25 4.25L13 9.25");
}

:global(.qcgfb0dhz) {
  d: path("m16.907 5.472l2.121 2.121L5.593 21.028l-2.121-2.121Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
