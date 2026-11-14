<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a3ut4l7re"/><path class="m0vi4fbwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-locksmith" {...props}></Icon>
<style>
:global(.a3ut4l7re) {
  d: path("M10.5 8.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM12 12l-8.5 8.5m2.25-2.25l2 2m.5-4.5l1.5 1.5");
}

:global(.m0vi4fbwj) {
  d: path("M14 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
