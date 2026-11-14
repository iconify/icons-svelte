<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nwytiqrbv"/><path class="unzt6uboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blood-transfusion" {...props}></Icon>
<style>
:global(.nwytiqrbv) {
  d: path("M3.5 3.25h9v10.5h-9ZM8 13.75c0 5 4 2.5 7.5 7m-4.5 0h10.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.unzt6uboc) {
  d: path("M8 6.25c1.5 1.75 1.75 2.5 1.75 3a1.75 1.75 0 0 1-3.5 0c0-.5.25-1.25 1.75-3Z");
}

</style>
