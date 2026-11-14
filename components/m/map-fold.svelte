<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klb4a5s6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:map-fold" {...props}></Icon>
<style>
:global(.klb4a5s6y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 5.5l6-2.5l7 2.5l6-2.5v15.5l-6 2.5l-7-2.5l-6 2.5Zm6-2.5v15.5m7-13V21");
}

</style>
