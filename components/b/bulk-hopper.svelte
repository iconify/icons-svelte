<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omnvl261q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bulk-hopper" {...props}></Icon>
<style>
:global(.omnvl261q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h16V11l-5.5 5.5h-5L4 11Zm6.25 13v4h3.5v-4");
}

</style>
