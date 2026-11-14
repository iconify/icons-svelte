<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dqb8_vbxt"/><path class="we_b95bsc"/><path class="sbezkcbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coming-soon" {...props}></Icon>
<style>
:global(.dqb8_vbxt) {
  d: path("M7.5 2.5c2.25 1.75 3 4.25 3 7V13h-6V9.5c0-2.75.75-5.25 3-7Zm-3 7l-1.75 2.25v2.75L4.5 13m6-3.5l1.75 2.25v2.75L10.5 13M6 13h3l.5 2h-4Z");
}

:global(.sbezkcbzn) {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.we_b95bsc) {
  d: path("M6.25 7.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-.5 7.5h3.5c0 2.25-.5 3.75-1.75 5.5c-1.25-1.75-1.75-3.25-1.75-5.5Zm9.75-.25h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

</style>
