<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4_k4t33w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:agency-office" {...props}></Icon>
<style>
:global(.q4_k4t33w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19m-17 0v9m9.5-9v9h5.5v-9M6.5 8l4-4l4 4v4.5h-8Zm7.5 8.75h5.5");
}

</style>
