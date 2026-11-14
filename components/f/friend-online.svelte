<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="so1xk_uzd"/><path class="g93vh7bpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:friend-online" {...props}></Icon>
<style>
:global(.g93vh7bpf) {
  fill: currentColor;
  d: path("M15.5 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.so1xk_uzd) {
  d: path("M6.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3 14c0-4.5 3.25-7 7-7c1.25 0 2.25.2 3 .5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
