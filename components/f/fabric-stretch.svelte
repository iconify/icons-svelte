<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eexe1emrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fabric-stretch" {...props}></Icon>
<style>
:global(.eexe1emrp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7q2.5-1.5 5 0t5 0v10q-2.5-1.5-5 0t-5 0Zm-4.5 5h19M4.25 10.25L2.5 12l1.75 1.75m15.5-3.5L21.5 12l-1.75 1.75");
}

</style>
