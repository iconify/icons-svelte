<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="toa6e6kuk"/><path class="bwljf1bmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:block-add" {...props}></Icon>
<style>
:global(.bwljf1bmn) {
  d: path("m3.5 7.5l8.5 5l8.5-5m-8.5 5v9m6-6.5v6m-3-3h6");
}

:global(.toa6e6kuk) {
  d: path("M13.227 20.778L12 21.5l-8.5-5v-9l8.5-5l8.5 5v4.738");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
