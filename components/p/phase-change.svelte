<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jell3uo9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:phase-change" {...props}></Icon>
<style>
:global(.jell3uo9n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H10v8H2.5Zm14.75-2s4.25 4.5 4.25 7a4.25 4.25 0 0 1-8.5 0c0-2.5 4.25-7 4.25-7Zm-13-7q-1.5 1.5 0 3t0 3m4-6q-1.5 1.5 0 3t0 3");
}

</style>
