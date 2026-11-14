<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voiqxdbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:event-source" {...props}></Icon>
<style>
:global(.voiqxdbda) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h12v4h-12Zm0 6.75h12v4h-12Zm0 6.75h12v4h-12Zm14.75-4.75h4.25M19 9.75l2.5 2.5l-2.5 2.5");
}

</style>
