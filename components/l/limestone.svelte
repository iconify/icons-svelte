<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd07_j-zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:limestone" {...props}></Icon>
<style>
:global(.fd07_j-zw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 15l3-9l7-2.5l6.5 3l1.5 8l-5.5 6l-8-.5Zm6-5.5h.01M15.5 11h.01m-5.01 4.5h.01");
}

</style>
