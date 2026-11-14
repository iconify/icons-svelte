<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rilv2u3lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:leaf-holly" {...props}></Icon>
<style>
:global(.rilv2u3lj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5q1.5 2.5 4.5 3q-1 3 2.5 5.5q-3.5 2-2.5 5.5q-3 0-4.5 3q-1.5-3-4.5-3Q8.5 13 5 11q3.5-2.5 2.5-5.5q3-.5 4.5-3Zm0 17v2m0-2v-12");
}

</style>
