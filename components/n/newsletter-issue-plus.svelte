<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="skysxo_4d"/><path class="yrbj1_p-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:newsletter-issue-plus" {...props}></Icon>
<style>
:global(.skysxo_4d) {
  d: path("M15.2 21.5H3.5v-19h15v9.7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yrbj1_p-c) {
  d: path("m7 6l4 3l4-3m-8 6.5h8m-8 4h4m7-1.5v6m-3-3h6");
}

</style>
