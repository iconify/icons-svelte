<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3-4ukb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:palm-island" {...props}></Icon>
<style>
:global(.a3-4ukb0c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20c0-3 4-5 8-5s8 2 8 5Zm8-5c0-3 1-6 1-9m0 0c-3-1-5 0-6.5 2M13 6c3-1 5 0 6.5 2M13 6c-1-2.5-3-3-4.5-2.5");
}

</style>
