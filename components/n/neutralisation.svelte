<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sn6dsipbn"/><path class="c_f752ybl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:neutralisation" {...props}></Icon>
<style>
:global(.c_f752ybl) {
  d: path("M10.25 14h4L12 19");
}

:global(.sn6dsipbn) {
  d: path("M8.5 3h7M10 3v6L4.5 19.25q-.75 2.25 1.75 2.25h11.5q2.5 0 1.75-2.25L14 9V3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
