<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghd8n4gkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:light-trails" {...props}></Icon>
<style>
:global(.ghd8n4gkm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 20.5l7-17m11 17l-7-17m-6 17c.5-4.5 3.5-5.5 2.5-9.5m5.5 9.5c-.5-4.5-3.5-5.5-2.5-9.5");
}

</style>
