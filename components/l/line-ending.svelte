<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="twz1a5qvw"/><path class="pigujfort"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:line-ending" {...props}></Icon>
<style>
:global(.pigujfort) {
  d: path("M10.5 13.5L7 17l3.5 3.5");
}

:global(.twz1a5qvw) {
  d: path("M3 5h18M3 10h11m5-.5V15q0 2-2 2H7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
