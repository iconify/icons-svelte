<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukmof7lme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aqueduct" {...props}></Icon>
<style>
:global(.ukmof7lme) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18V8H3ZM3 8v13M21 8v13M3 14a3 3 0 0 1 6 0v7m0-7a3 3 0 0 1 6 0v7m0-7a3 3 0 0 1 6 0");
}

</style>
