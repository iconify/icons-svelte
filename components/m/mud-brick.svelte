<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s52uzybxk"/><path class="tag7x2b-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mud-brick" {...props}></Icon>
<style>
:global(.s52uzybxk) {
  d: path("M2.5 11L6 7.5h15.5V14L18 17.5H2.5Z");
}

:global(.tag7x2b-n) {
  d: path("M2.5 11H18v6.5m0-6.5l3.5-3.5M6 14.25h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
