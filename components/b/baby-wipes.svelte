<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l9ny2xiaj"/><path class="wqi72eb3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:baby-wipes" {...props}></Icon>
<style>
:global(.l9ny2xiaj) {
  d: path("M3.5 9h17a1 1 0 0 1 1 1v10.5a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1Zm5 0l-1-6q2.5-1 4.5.5t4.5-.5l-1 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wqi72eb3r) {
  d: path("M7 12.5h10V18H7Z");
}

</style>
