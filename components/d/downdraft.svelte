<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glw-_eakv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:downdraft" {...props}></Icon>
<style>
:global(.glw-_eakv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 11.75h8.5a2.5 2.5 0 0 0 0-5a4.25 4.25 0 0 0-8.5 0a2.5 2.5 0 0 0 0 5M12 14.5v7m-3.75-3.75L12 21.5l3.75-3.75");
}

</style>
