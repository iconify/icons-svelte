<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_3fmrb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mirror-object" {...props}></Icon>
<style>
:global(.i_3fmrb5p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4.5v15H3.5V10Zm6 0v15h5.5V10Zm-3-2V5m0 3.5V11m0 3.5V17m0 3.5v1");
}

</style>
