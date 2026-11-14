<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ignhhxb1k"/><path class="ij7cb2b5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dental-checkup" {...props}></Icon>
<style>
:global(.ignhhxb1k) {
  d: path("M10 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm1.5 3.5l-8 8");
}

:global(.ij7cb2b5u) {
  d: path("M12.75 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm2 10.5l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
