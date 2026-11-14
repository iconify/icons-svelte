<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jesvjub2n"/><path class="tths0dbed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hangman" {...props}></Icon>
<style>
:global(.jesvjub2n) {
  d: path("M4.5 21.5h10m-6.5 0v-18h8.5V6");
}

:global(.tths0dbed) {
  d: path("M14 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 2.5v5m-3-3h6m-3 3L14 19.5m2.5-3.5l2.5 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
