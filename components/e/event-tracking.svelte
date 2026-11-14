<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dhugf2w8a"/><path class="yfb3sr1vn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:event-tracking" {...props}></Icon>
<style>
:global(.dhugf2w8a) {
  d: path("m2.5 12l5-6.5h14v13h-14Zm5 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yfb3sr1vn) {
  d: path("m16 7.75l-4.25 4.75H15l-1.25 3.75l4.25-5h-3Z");
}

</style>
