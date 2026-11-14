<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-ckxc4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hiking-boots" {...props}></Icon>
<style>
:global(.j2-ckxc4w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h6V11l7.5 3c1 .5 1.5 1.5 1.5 2.5V18H5.5v-6ZM5.5 15H21M8 7h4");
}

</style>
