<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jbo2ibbko"/><path class="mewl0mb5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:astronaut-salute" {...props}></Icon>
<style>
:global(.jbo2ibbko) {
  d: path("M7.75 5.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm-.75 6h8v6H7Zm2 6v4m4-4v4M7 14l-2.5 3");
}

:global(.mewl0mb5m) {
  d: path("m15 14l3.5-3.5L14.25 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
