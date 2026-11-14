<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf3zuwb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:briefcase-arrow" {...props}></Icon>
<style>
:global(.gf3zuwb-u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5H16v11H2.5Zm4.5 0V5h4.5v2.5m-9 4.5H16m0 3.5h5.5M19 13l2.5 2.5L19 18");
}

</style>
