<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yuopji0ht"/><path class="qljz65b7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bug" {...props}></Icon>
<style>
:global(.qljz65b7y) {
  d: path("M9 8.75a3 3 0 0 1 6 0M12 11v9.5M3.5 10L7 11.5M20.5 10L17 11.5m-14 3h4m14 0h-4m-13.5 5l3.75-2m13.25 2l-3.75-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yuopji0ht) {
  d: path("M7 14a5 6.5 0 1 0 10 0a5 6.5 0 1 0-10 0Z");
}

</style>
