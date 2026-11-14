<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iysj_2bst"/><path class="veeox7o8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:paper-towel-holder" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iysj_2bst) {
  d: path("M3.5 5v9m0-4.5h8M7 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.veeox7o8p) {
  d: path("M11.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.5 0V21");
}

</style>
