<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8-8lk-_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:focus-mode" {...props}></Icon>
<style>
:global(.z8-8lk-_t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0M12 3.5v4m0 9v4M3.5 12h4m9 0h4M12 12h.01");
}

</style>
