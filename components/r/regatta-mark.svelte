<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8smkhquo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:regatta-mark" {...props}></Icon>
<style>
:global(.m8smkhquo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m4.5 4.5V17m-7 0h14l-1.5 3.5h-11Z");
}

</style>
