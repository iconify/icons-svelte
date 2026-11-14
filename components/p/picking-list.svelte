<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kfqebjbah"/><path class="o2l9w1_cd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:picking-list" {...props}></Icon>
<style>
:global(.kfqebjbah) {
  d: path("M4.5 3.5h15v17h-15Z");
}

:global(.o2l9w1_cd) {
  d: path("M8 8.5L9.5 10L12 7m-4 7l1.5 1.5l2.5-3M14 9h2m-2 5.5h2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
