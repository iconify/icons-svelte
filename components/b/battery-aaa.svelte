<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfw0ozbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-aaa" {...props}></Icon>
<style>
:global(.wfw0ozbuf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4.75h9V21.5h-9Zm3 0V2.5h3v2.25m-6 7.75h9");
}

</style>
