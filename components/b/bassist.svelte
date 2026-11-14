<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xjbak4i9p"/><path class="r4sma8b4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bassist" {...props}></Icon>
<style>
:global(.r4sma8b4y) {
  d: path("m11.081 11.152l7.071-7.071l1.767 1.767l-7.071 7.071ZM17.5 3.5l3 3M6.25 14.25l3.5 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xjbak4i9p) {
  d: path("M2.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
