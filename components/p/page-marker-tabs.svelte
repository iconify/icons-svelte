<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eys4_vb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:page-marker-tabs" {...props}></Icon>
<style>
:global(.eys4_vb4o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5H17v19H3.5ZM17 5h3a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1h-3m0 3h3a1 1 0 0 1 1 1V16a1 1 0 0 1-1 1h-3M7 7.5h6.5m-6.5 4h4.5");
}

</style>
