<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-qmtqbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:function-sharp" {...props}></Icon>
<style>
:global(.h-qmtqbrh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 3.75h-1l-2.273-.011L10.5 6L9.25 18l-.227 2.261l-2.273-.011H5.5M7.25 9.5h6m1.25 3.25l5 5.5m0-5.5l-5 5.5");
}

</style>
