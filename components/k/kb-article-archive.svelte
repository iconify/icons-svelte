<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iqgmv9b7j"/><path class="g97j9x61h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kb-article-archive" {...props}></Icon>
<style>
:global(.g97j9x61h) {
  d: path("M13.5 2.5V6H17M9.5 16.75h5");
}

:global(.iqgmv9b7j) {
  d: path("M2.5 12.5h19M4 12.5V19a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-6.5m-13 0v-8a2 2 0 0 1 2-2h4.5L17 6v6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
