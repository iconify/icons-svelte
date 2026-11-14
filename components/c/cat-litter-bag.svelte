<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i8voe_h3l"/><path class="vecl8hbxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cat-litter-bag" {...props}></Icon>
<style>
:global(.i8voe_h3l) {
  d: path("M5 3h14l1.5 18.75h-17Zm0 3.25h14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vecl8hbxi) {
  d: path("m7.75 9l2.75 3h3l2.75-3v5.75a4.25 4.25 0 0 1-8.5 0Zm2.75 5.75h.01m2.99 0h.01");
}

</style>
