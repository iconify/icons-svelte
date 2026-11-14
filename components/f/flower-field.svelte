<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1pm7ybsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flower-field" {...props}></Icon>
<style>
:global(.j1pm7ybsy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19M12.75 5.25a1 1 0 1 1 .5 1.5A1 1 0 1 1 12 7.5a1 1 0 1 1-1.25-.75a1 1 0 1 1 .5-1.5a1 1 0 1 1 1.5 0M12 7.5V20m-5.75-8a1 1 0 1 1 .5 1.5a1 1 0 1 1-1.25.75a1 1 0 1 1-1.25-.75a1 1 0 1 1 .5-1.5a1 1 0 1 1 1.5 0m-.75 2.25V20m13.75-9.5a1 1 0 1 1 .5 1.5a1 1 0 1 1-1.25.75a1 1 0 1 1-1.25-.75a1 1 0 1 1 .5-1.5a1 1 0 1 1 1.5 0m-.75 2.25V20");
}

</style>
