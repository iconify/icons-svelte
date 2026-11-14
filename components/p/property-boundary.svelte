<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouv1bk5bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:property-boundary" {...props}></Icon>
<style>
:global(.ouv1bk5bw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h19m-18 0V9l1-2l1 2v12.5m5.5 0V9l1-2l1 2v12.5m5.5 0V9l1-2l1 2v12.5M7 14h2.5m5 0H17");
}

</style>
