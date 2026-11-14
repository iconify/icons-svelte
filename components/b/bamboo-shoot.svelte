<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uo9-5sdbh"/><path class="fg-_bobtm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bamboo-shoot" {...props}></Icon>
<style>
:global(.fg-_bobtm) {
  d: path("M8.75 15.25Q12 17 15.5 15m-5.75-4.5q2.75 1.25 5.25-.25m-.75-3.75q2.25-3 5.25-3.5M4 20.5h16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uo9-5sdbh) {
  d: path("M8.5 20.5c0-7.5 2-12.5 5-16.5c1.5 5 2 10 2 16.5");
}

</style>
