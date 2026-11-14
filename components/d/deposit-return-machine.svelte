<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n141exw_n"/><path class="rddx62b0o"/><path class="twl2tptcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deposit-return-machine" {...props}></Icon>
<style>
:global(.n141exw_n) {
  d: path("M15.5 20.9v.6h-12v-19h12v8.6");
}

:global(.rddx62b0o) {
  d: path("M8.5 5.5h2V7l1 1.5V13h-4V8.5l1-1.5ZM6 16v2h5.25v-1.35m10.25 4.6V18.5A2.5 2.5 0 0 0 19 16h-4.25");
}

:global(.twl2tptcd) {
  d: path("M16.75 13.75L14.5 16l2.25 2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
