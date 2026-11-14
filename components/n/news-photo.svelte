<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wffwdccte"/><path class="h2844mzsd"/><path class="x7xqwibku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:news-photo" {...props}></Icon>
<style>
:global(.h2844mzsd) {
  d: path("M7 5.5h10V14H7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wffwdccte) {
  d: path("M4 2.5h16v19H4Z");
}

:global(.x7xqwibku) {
  d: path("M9.5 14v-3.5l2.5-2l2.5 2V14M7 17.5h10");
}

</style>
