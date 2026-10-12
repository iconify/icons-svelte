<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsxps__sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:board-eraser-sharp" {...props}></Icon>
<style>
:global(.wsxps__sb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 5.25h14.5v6.5H4.75zm-2 6.5h18.5v5H2.75zm6-3.25h6.5m-10.5 12h4m3 0h7.5");
}

</style>
