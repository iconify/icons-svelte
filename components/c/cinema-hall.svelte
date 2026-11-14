<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bauwzxbvg"/><path class="tp7u0ubgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cinema-hall" {...props}></Icon>
<style>
:global(.bauwzxbvg) {
  d: path("M2.5 3.5h19V10h-19Zm2 6.5v10.5h15V10M7 6.75h.01m4.99 0h.01m4.99 0h.01");
}

:global(.tp7u0ubgd) {
  d: path("M9.5 20.5v-7h5v7m-2.5-7v7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
