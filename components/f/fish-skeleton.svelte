<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhqnsebwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fish-skeleton" {...props}></Icon>
<style>
:global(.qhqnsebwo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 7.5c3.5 0 5 2.5 5 4.5s-1.5 4.5-5 4.5ZM4.5 12h12m-9-3v6m3-6.5v7m3-7.5v8m-11-7.5l2 3.5l-2 3.5");
}

</style>
