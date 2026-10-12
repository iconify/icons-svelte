<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_b7tnddm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:backpack-travel-sharp" {...props}></Icon>
<style>
:global(.q_b7tnddm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 7.25a2.75 2.75 0 0 1 5.5 0m-9.5 0h13.5v14H5.25zM9 15h6");
}

</style>
