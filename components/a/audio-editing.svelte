<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq3wfacsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:audio-editing" {...props}></Icon>
<style>
:global(.tq3wfacsh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19v13h-19ZM12 16v4.5m-3.5 0h7m-9-13v4M9.25 6v7M12 8.5v2m2.75-3.75v5.5m2.75-4v2.5");
}

</style>
