<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njt26rq6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pollen-tree" {...props}></Icon>
<style>
:global(.njt26rq6z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9a6 6 0 1 0 12 0A6 6 0 1 0 4 9m6 6v6m9-15h.01m1.49 4.5h.01m-1.51 4h.01");
}

</style>
