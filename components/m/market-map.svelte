<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ux67-2psj"/><path class="b8_xx6o1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:market-map" {...props}></Icon>
<style>
:global(.b8_xx6o1x) {
  d: path("M18.5 21.5s-3-3-3-5.5a3 3 0 0 1 6 0c0 2.5-3 5.5-3 5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux67-2psj) {
  d: path("M12.914 17.882L12.5 18l-5-2l-5 2V5.5l5-2l5 2l7-2v6.75M7.5 3.5V16m5-10.5V18");
}

</style>
