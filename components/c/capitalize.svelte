<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui-lr81kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:capitalize" {...props}></Icon>
<style>
:global(.ui-lr81kr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h9M7 5v15m9.5-11.5v9a2 2 0 0 0 2 2H20M14 12h6");
}

</style>
