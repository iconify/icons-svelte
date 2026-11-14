<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr30rmbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:neutral-earth" {...props}></Icon>
<style>
:global(.yr30rmbvf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19M12 4v9m-6.5 0h13M8 16.75h8m-5.75 3.75h3.5");
}

</style>
