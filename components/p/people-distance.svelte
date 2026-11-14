<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez2jdccnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:people-distance" {...props}></Icon>
<style>
:global(.ez2jdccnc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M2.5 14.5v-.75a3.5 3.5 0 0 1 7 0v.75M15.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-1.25 9.5v-.75a3.5 3.5 0 0 1 7 0v.75M5 17.5l-2 2l2 2m-2-2h18m-2-2l2 2l-2 2");
}

</style>
