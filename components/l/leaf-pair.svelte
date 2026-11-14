<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_22vdb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-pair" {...props}></Icon>
<style>
:global(.z_22vdb-s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11c0-4.5-3-7-8.5-7c0 4.5 3 7 8.5 7m0 0c0-4.5 3-7 8.5-7c0 4.5-3 7-8.5 7m0 0v10");
}

</style>
