<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ke58ybbzd"/><path class="efdp_dbyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:house-door-open" {...props}></Icon>
<style>
:global(.efdp_dbyu) {
  d: path("M7.5 20.5v-8H13v8m0-8l3.5-1.5v6.25l-3.5 1.5Z");
}

:global(.ke58ybbzd) {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
