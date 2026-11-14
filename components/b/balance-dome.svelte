<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi4rwvjkb"/><path class="s8q_ybbid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:balance-dome" {...props}></Icon>
<style>
:global(.s8q_ybbid) {
  d: path("M6.5 10.5c3 1.5 8 1.5 11 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vi4rwvjkb) {
  d: path("M4 15.5a8 8 0 0 1 16 0m-17.5 0h19V19h-19Z");
}

</style>
