<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1t1tgbip"/><path class="lcz74t6md"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electric-blanket" {...props}></Icon>
<style>
:global(.f1t1tgbip) {
  d: path("M2.5 12.5h19V21h-19Z");
}

:global(.lcz74t6md) {
  d: path("M2.5 16.75H15l3.5-4.25m-9 0V21M7 9.5Q5.5 7.75 7 6t0-3.5m5 7Q10.5 7.75 12 6t0-3.5m5 7Q15.5 7.75 17 6t0-3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
