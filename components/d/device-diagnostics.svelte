<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="slt7slekb"/><path class="mc6rb7jhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:device-diagnostics" {...props}></Icon>
<style>
:global(.mc6rb7jhs) {
  d: path("M7 10.5h2l1.5-3L13 13l1.5-2.5H17");
}

:global(.slt7slekb) {
  d: path("M4.5 4.5h15v11h-15Zm-2 14h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
