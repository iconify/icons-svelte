<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8u760b4u"/><path class="svkwq82ml"/><path class="p-xk61mdx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bear-market" {...props}></Icon>
<style>
:global(.p-xk61mdx) {
  d: path("M15.5 13.5h4v-4");
}

:global(.p8u760b4u) {
  d: path("M3.5 3v17.5H21");
}

:global(.svkwq82ml) {
  d: path("m7 5.5l4 5L14 8l5.5 5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
