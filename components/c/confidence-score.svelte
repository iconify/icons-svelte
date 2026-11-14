<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4rmd6rmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:confidence-score" {...props}></Icon>
<style>
:global(.h4rmd6rmz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5a9.5 9.5 0 0 1 14.25-8.25m3.5 3.5a9.5 9.5 0 0 1 1.25 4.75m-9.5 0l3-5.25m-3 5.25h.01");
}

</style>
