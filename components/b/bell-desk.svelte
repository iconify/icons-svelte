<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vms2gdb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bell-desk" {...props}></Icon>
<style>
:global(.vms2gdb6o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 16.5a7.5 7.5 0 0 1 15 0M3 16.5h18M12 5v4m-2-4h4M2.5 20h19");
}

</style>
