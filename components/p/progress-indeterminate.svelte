<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvuhdzb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:progress-indeterminate" {...props}></Icon>
<style>
:global(.bvuhdzb6d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8h15a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Zm2 8l3-8m1 8l3-8m1 8l3-8");
}

</style>
