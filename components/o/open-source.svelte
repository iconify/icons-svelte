<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jcj58450t"/><path class="jskqodb1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:open-source" {...props}></Icon>
<style>
:global(.jcj58450t) {
  d: path("M4 8.5h16V18a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 4 18Zm0 0l-1.5-5h5m12.5 5l1.5-5h-5");
}

:global(.jskqodb1q) {
  d: path("m9.5 11.5l-2.75 3l2.75 3m5-6l2.75 3l-2.75 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
