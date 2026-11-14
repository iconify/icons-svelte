<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj6xxw89v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dental-probe" {...props}></Icon>
<style>
:global(.bj6xxw89v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 18.5L9 13l2 2l-5.5 5.5ZM10 14l7-7m0 0l1.75-1.75c2-2-.75-2.75-1.75-1");
}

</style>
