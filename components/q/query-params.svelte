<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz0t2g7em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:query-params" {...props}></Icon>
<style>
:global(.uz0t2g7em) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 6l-4.5 6L7 18M17 6l4.5 6l-4.5 6M9.5 9a2.5 2.5 0 1 1 3.5 2.25c-.75.25-1 1-1 1.75v.5m0 3.5h.01");
}

</style>
