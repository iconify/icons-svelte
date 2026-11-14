<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opr1tbypw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:laser-beam" {...props}></Icon>
<style>
:global(.opr1tbypw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5h7v7h-7Zm7 3.5h5.75M18 12h3.5m-4.25-2l2.5-2.5m-2.5 6.5l2.5 2.5");
}

</style>
