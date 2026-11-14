<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjlpou4md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:poll-multi-choice" {...props}></Icon>
<style>
:global(.xjlpou4md) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h12V7h-12Zm0 7.25h12v4.5h-12Zm0 7.25h12v4.5h-12Zm-7-12.5l2 2l3-3m-5 8.25l2 2l3-3");
}

</style>
