<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3qfjvbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gantt-zoom-in" {...props}></Icon>
<style>
:global(.b3qfjvbjt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v18m9-16h8m-12 5h8m-10 5h5m6.5 0v6m-3-3h6");
}

</style>
