<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9cd2vbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:distillation-flask" {...props}></Icon>
<style>
:global(.z9cd2vbht) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3v5.25a6.5 6.5 0 1 0 3 0V3m0 2.5l8.5 5m-4.25-5.75L19 6.5");
}

</style>
