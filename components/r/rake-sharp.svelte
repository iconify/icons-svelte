<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkduubcix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rake-sharp" {...props}></Icon>
<style>
:global(.qkduubcix) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v10m-7.75 0h15.5v3H4.25zm1.75 3v5.5m4-5.5v5.5m4-5.5v5.5m4-5.5v5.5");
}

</style>
