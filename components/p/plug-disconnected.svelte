<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw9xix4ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:plug-disconnected" {...props}></Icon>
<style>
:global(.fw9xix4ra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.5h10v3a5 5 0 0 1-10 0ZM4 3h16M9.5 7v3.5m5-3.5v3.5m-2.5 8v3");
}

</style>
