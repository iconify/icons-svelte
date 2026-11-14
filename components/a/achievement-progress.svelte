<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t3eoqbcex"/><path class="cih01l2-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:achievement-progress" {...props}></Icon>
<style>
:global(.cih01l2-e) {
  d: path("m12 8l1 2.5l2.75.25l-2 1.75l.5 2.75L12 14l-2.25 1.25l.5-2.75l-2-1.75L11 10.5Z");
}

:global(.t3eoqbcex) {
  d: path("M3 12a9 9 0 1 1 11.781 8.56");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
