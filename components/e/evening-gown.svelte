<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqn-p1pco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:evening-gown" {...props}></Icon>
<style>
:global(.rqn-p1pco) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6.5q3 1.5 6 0l-.5 5l5 8.5q-7.5 2.5-15 0l5-8.5Zm.25-4L9 6.5m5.75-4l.25 4m-5.5 5h5");
}

</style>
