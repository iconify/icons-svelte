<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sql0-iz5y"/><path class="gpwm9kbzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:elephant-head" {...props}></Icon>
<style>
:global(.gpwm9kbzp) {
  d: path("M8.75 6C4 3.5 2.25 6.5 2.5 10s3 5 6.5 2.25M15.25 6c4.75-2.5 6.5.5 6.25 4s-3 5-6.5 2.25m-4.5-3.5h.01m2.99 0h.01");
}

:global(.sql0-iz5y) {
  d: path("M8.25 11c0-5 1.5-7.5 3.75-7.5S15.75 6 15.75 11L12 13.25ZM12 13.25v5.25c0 2.25 3 2.75 3.75.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
