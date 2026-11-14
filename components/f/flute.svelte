<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmkg7su7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flute" {...props}></Icon>
<style>
:global(.kmkg7su7q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.277 18.187l15.91-15.91l3.536 3.536l-15.91 15.91ZM15.25 8.75l1.5-1.5M7 17h.01m2.24-2.25h.01m2.24-2.25h.01");
}

</style>
