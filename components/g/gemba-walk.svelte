<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzznfobby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gemba-walk" {...props}></Icon>
<style>
:global(.bzznfobby) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.75a2.75 4 0 1 0 5.5 0a2.75 4 0 1 0-5.5 0m9 3.25a2.75 4 0 1 0 5.5 0a2.75 4 0 1 0-5.5 0m-8.5 4.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0m9 3.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0");
}

</style>
