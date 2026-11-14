<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho7k-abyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:map-add-place" {...props}></Icon>
<style>
:global(.ho7k-abyu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.186 19.553L8.5 18.5l-6 2v-15l6-2l7 2l6-2v11.671M8.5 3.5v15m7-13v6.7M18 15v6m-3-3h6");
}

</style>
