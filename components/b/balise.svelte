<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwxm5cc4m"/><path class="kl0lk4qlc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:balise" {...props}></Icon>
<style>
:global(.jwxm5cc4m) {
  d: path("M3 15h18v5H3Zm6.5-3.5a3.5 3.5 0 0 1 5 0m-7-2a6.5 6.5 0 0 1 9 0");
}

:global(.kl0lk4qlc) {
  d: path("M5.25 7.25a9.5 9.5 0 0 1 13.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
