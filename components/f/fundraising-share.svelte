<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ajkp7fb5u"/><path class="zanu6abbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fundraising-share" {...props}></Icon>
<style>
:global(.ajkp7fb5u) {
  d: path("M15.064 15.295L7 11.5H2.5v-4H7L15.5 3v11.782M5 11.5l1.25 5m8.75 5c0-3 1.75-4 5.75-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zanu6abbg) {
  d: path("m18.75 15.5l2 2l-2 2");
}

</style>
