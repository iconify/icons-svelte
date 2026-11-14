<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="innil8rbj"/><path class="w88g4d7pa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ball-bearing" {...props}></Icon>
<style>
:global(.innil8rbj) {
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w88g4d7pa) {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.75 9.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-11.5 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
