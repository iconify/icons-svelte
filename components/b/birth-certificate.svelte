<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iyxsvtbea"/><path class="eq86yulva"/><path class="dm6_t0uzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:birth-certificate" {...props}></Icon>
<style>
:global(.dm6_t0uzv) {
  d: path("M5.75 7.5h.01M7.5 7h.01m1.74.5h.01M12 8h4.5m-1.75 8.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm1.5 2.5l-.75 2.75M18.75 19l.75 2.75");
}

:global(.eq86yulva) {
  fill: currentColor;
  d: path("M5.75 11a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Z");
}

:global(.iyxsvtbea) {
  d: path("M12 17H2.5V3.5h19v9.2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
