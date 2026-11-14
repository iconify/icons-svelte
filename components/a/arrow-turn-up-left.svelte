<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ksbtii-5g"/><path class="arzl-3bao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-turn-up-left" {...props}></Icon>
<style>
:global(.arzl-3bao) {
  d: path("m3.5 9l4-4l4 4");
}

:global(.ksbtii-5g) {
  d: path("M20.5 19h-8a5 5 0 0 1-5-5V5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
