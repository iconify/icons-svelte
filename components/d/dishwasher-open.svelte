<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="blvwpmb4u"/><path class="qjp3ou2ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dishwasher-open" {...props}></Icon>
<style>
:global(.blvwpmb4u) {
  d: path("M4 2.5h16V16H4ZM4 16h16l1.5 5.5h-19ZM4 6h16");
}

:global(.qjp3ou2ni) {
  d: path("M8 16a4 4 0 0 1 8 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
