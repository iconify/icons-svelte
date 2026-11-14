<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7e8r8buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:booth-backdrop" {...props}></Icon>
<style>
:global(.f7e8r8buw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19l-1.5 2l1.5 2h-19l1.5-2Zm2 4h15v11h-15Zm2.5 11V21m10-3.5V21M5 21h4m6 0h4");
}

</style>
