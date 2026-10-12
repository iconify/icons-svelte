<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue1u3ub-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:collection-grid-sharp" {...props}></Icon>
<style>
:global(.ue1u3ub-c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h8v8h-8zm10.5 0h8v8h-8zm-10.5 10.5h8v8h-8zm12 1.25v-1.25h6v8.444l-.95-.594l-2.05-1.5l-2.05 1.5l-.95.594V20.6Z");
}

</style>
