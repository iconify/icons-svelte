<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceowqhbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pen-display-sharp" {...props}></Icon>
<style>
:global(.ceowqhbkv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5v13.5H2.75zm4.75 13.5l-1.75 4.5m10.75-4.5l1.75 4.5M9 12.75l6.25-6.25");
}

</style>
