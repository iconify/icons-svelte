<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knmtq-uqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-health" {...props}></Icon>
<style>
:global(.knmtq-uqp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5s-8.5-5-8.5-11a4.5 4.5 0 0 1 8.5-2a4.5 4.5 0 0 1 8.5 2c0 6-8.5 11-8.5 11ZM12 10v5m-2.5-2.5h5");
}

</style>
