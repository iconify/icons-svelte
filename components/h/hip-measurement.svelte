<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uqk735lfa"/><path class="q_4lklbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hip-measurement" {...props}></Icon>
<style>
:global(.q_4lklbts) {
  d: path("M10 5.75L8.25 7.5L10 9.25Zm4 0l1.75 1.75L14 9.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uqk735lfa) {
  d: path("M5 2.5h14l1.5 19h-6L12 11L9.5 21.5h-6Zm3.25 5h7.5");
}

</style>
