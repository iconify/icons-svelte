<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o7y6k3b2a"/><path class="qi3xiibto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lab-oven" {...props}></Icon>
<style>
:global(.o7y6k3b2a) {
  d: path("M3 3h18v18H3Zm0 6h18");
}

:global(.qi3xiibto) {
  d: path("M7 12h10v6H7Zm0-6h.01M11 6h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
