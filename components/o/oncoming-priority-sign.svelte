<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tkh-ztz9c"/><path class="jiijv7bbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:oncoming-priority-sign" {...props}></Icon>
<style>
:global(.jiijv7bbp) {
  d: path("M5.75 9.25L8.5 6.5l2.75 2.75M16 7v6m-2-2l2 2l2-2");
}

:global(.tkh-ztz9c) {
  d: path("M3 3h18v18H3Zm5.5 15V6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
