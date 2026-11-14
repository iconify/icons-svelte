<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf70j2i9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:investor" {...props}></Icon>
<style>
:global(.xf70j2i9a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5c0-3.25 2.25-5.25 4.75-5.25s4.5 2 4.5 5.25ZM15 11h6.5v9.5H15ZM4.25 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM15 14.25h6.5M15 17.5h6.5");
}

</style>
