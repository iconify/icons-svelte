<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e5ajikb4j"/><path class="oq9h3b2jm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bring-forward" {...props}></Icon>
<style>
:global(.e5ajikb4j) {
  d: path("M8 13.5H4.5a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2V8");
}

:global(.oq9h3b2jm) {
  d: path("M8 8h13.5v13.5H8Zm10.75 0V2.5M16.5 4.75l2.25-2.25L21 4.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
