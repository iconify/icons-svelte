<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="czqidacrf"/><path class="i8mwmkh-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-story" {...props}></Icon>
<style>
:global(.czqidacrf) {
  d: path("M12 6.5c-2-1.5-5-2-9.5-2V18c4.5 0 7.5.5 9.5 2c2-1.5 5-2 9.5-2V4.5c-4.5 0-7.5.5-9.5 2Zm0 0V20M5.5 9l3.5.75M5.5 12.5l3.5.75");
}

:global(.i8mwmkh-x) {
  d: path("m14.5 14.5l2-3.5l2 1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
