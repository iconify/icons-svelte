<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgci_x-ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:match-stats" {...props}></Icon>
<style>
:global(.zgci_x-ba) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.75h18m-17-9.5h3.25V17H4Zm6.25-6h3.25V17h-3.25Zm6.25 3.5h3.25V17H16.5Z");
}

</style>
