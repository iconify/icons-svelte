<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="whvb58bhv"/><path class="j1qb57b4m"/><path class="hbkond58l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:refresh-circle" {...props}></Icon>
<style>
:global(.hbkond58l) {
  d: path("m5.5 14l2-2l2 2");
}

:global(.j1qb57b4m) {
  d: path("m14.5 10l2 2l2-2m-2.603 4.25A4.5 4.5 0 0 1 7.5 12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.whvb58bhv) {
  d: path("M8.103 9.75A4.5 4.5 0 0 1 16.5 12");
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
