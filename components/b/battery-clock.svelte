<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x89iitb4u"/><path class="a6cpk6bfi"/><path class="r87sa_1ne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-clock" {...props}></Icon>
<style>
:global(.a6cpk6bfi) {
  d: path("M6.75 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.r87sa_1ne) {
  d: path("M10.75 10v2l1.5 1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x89iitb4u) {
  d: path("M2.5 5H19v14H2.5ZM19 9.5h1.5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H19");
}

</style>
