<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo3fuxmnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:breadcrumbs-pack" {...props}></Icon>
<style>
:global(.eo3fuxmnp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 10l3-2l3 2l3-2l3 2v9.5a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2ZM6 2.5l3.25.5l-.5 2.25l-3-.25Zm7.5.5l3.25-.5l.5 3l-3.25.25Zm4.25 6.5L21 9l.5 3.25l-3.25.25Z");
}

</style>
