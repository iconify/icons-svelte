<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwn332y_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:road-conditions" {...props}></Icon>
<style>
:global(.rwn332y_x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21.5l5.5-19m12.5 19l-5.5-19M12 3v4m-4 9.5a4 2 0 1 0 8 0a4 2 0 1 0-8 0Z");
}

</style>
