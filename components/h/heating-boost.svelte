<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaetuc9fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heating-boost" {...props}></Icon>
<style>
:global(.zaetuc9fb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5V5a2.5 2.5 0 0 1 5 0v8.5a4.25 4.25 0 1 1-5 0m12 7v-17m-3 3l3-3l3 3M8 9.5v7");
}

</style>
