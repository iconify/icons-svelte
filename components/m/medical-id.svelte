<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfenysb5q"/><path class="d5gn1wc6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:medical-id" {...props}></Icon>
<style>
:global(.d5gn1wc6y) {
  d: path("M11.125 7.5h1.75a2.625 2.625 0 0 1 2.625 2.625v2.25A2.625 2.625 0 0 1 12.875 15h-1.75A2.625 2.625 0 0 1 8.5 12.375v-2.25A2.625 2.625 0 0 1 11.125 7.5M12 9.25v4m-2-2h4m-3.5 7.25h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rfenysb5q) {
  d: path("M9.875 2.5h4.25A4.375 4.375 0 0 1 18.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 17.125V6.875A4.375 4.375 0 0 1 9.875 2.5");
}

</style>
