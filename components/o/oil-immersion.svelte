<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbd96uh7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:oil-immersion" {...props}></Icon>
<style>
:global(.mbd96uh7g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9v6l-2.5 5h-4l-2.5-5Zm0 3h9M12 16.25c1.25 1.25 2.25 2.25 2.25 3a2.25 2.25 0 0 1-4.5 0c0-.75 1-1.75 2.25-3");
}

</style>
