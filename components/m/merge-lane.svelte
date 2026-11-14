<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ddkgmjazk"/><path class="kk5fssb7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:merge-lane" {...props}></Icon>
<style>
:global(.ddkgmjazk) {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Zm0 15.25v-11");
}

:global(.kk5fssb7b) {
  d: path("M9.75 8.75L12 6.5l2.25 2.25m-5 6.75q0-2.5 2.75-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
