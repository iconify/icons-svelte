<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyyx26wqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cable-wakepark" {...props}></Icon>
<style>
:global(.cyyx26wqv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 4l19 5M9.75 8.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 11v4.5m-3 0h6M2.5 20q2.375-1.5 4.75 0T12 20t4.75 0t4.75 0");
}

</style>
