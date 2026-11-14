<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b59fimbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nursery" {...props}></Icon>
<style>
:global(.b59fimbjo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4v17.5M20.5 4v17.5M3.5 8h17m-17 9h17M8 8v9m4-9v9m4-9v9");
}

</style>
