<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i15_5jf4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:filter-press" {...props}></Icon>
<style>
:global(.i15_5jf4z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H6v15H2.5ZM18 4h3.5v15H18ZM6 5.5h12M9 8.25V17m3-8.75V17m3-8.75V17");
}

</style>
