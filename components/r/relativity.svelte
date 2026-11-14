<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f6xyxvbxw"/><path class="h-5oepxfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:relativity" {...props}></Icon>
<style>
:global(.f6xyxvbxw) {
  d: path("M2.5 11C8 11 9 16.5 12 16.5s4-5.5 9.5-5.5");
}

:global(.h-5oepxfq) {
  d: path("M2.5 15.5C8 15.5 9 21 12 21s4-5.5 9.5-5.5M9 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
