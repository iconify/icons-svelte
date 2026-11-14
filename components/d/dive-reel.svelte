<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i_jo6mb3j"/><path class="o0dfy9bhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dive-reel" {...props}></Icon>
<style>
:global(.i_jo6mb3j) {
  d: path("M2.5 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.o0dfy9bhh) {
  d: path("M7.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM10 4.5h7.5a3 3 0 0 1 3 3V20");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
