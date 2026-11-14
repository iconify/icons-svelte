<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm92wyf9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:incorporation" {...props}></Icon>
<style>
:global(.dm92wyf9b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.8 20.5H3V9h4.5V2.5h9v10.1m-6-6.1h.01m2.99 0h.01m-3.01 4h.01m2.99 0h.01M18 15v6m-3-3h6");
}

</style>
