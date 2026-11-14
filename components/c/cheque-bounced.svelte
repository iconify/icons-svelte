<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ajt41lbqe"/><path class="j3k03rc5l"/><path class="ausv3i8bo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cheque-bounced" {...props}></Icon>
<style>
:global(.ajt41lbqe) {
  d: path("M13.1 18.5H2.5v-13h19v7.3M6 9.5h5.5m-5.5 5h3.5");
}

:global(.ausv3i8bo) {
  d: path("m18.5 15.5l2.25.25L21 18");
}

:global(.j3k03rc5l) {
  d: path("m14.75 15.5l2.5 5l3.5-4.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
