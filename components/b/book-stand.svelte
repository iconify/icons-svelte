<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkyfo376d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:book-stand" {...props}></Icon>
<style>
:global(.lkyfo376d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5c-2.5-2-6-2.5-9-2v9c3-.5 6.5 0 9 2c2.5-2 6-2.5 9-2v-9c-3-.5-6.5 0-9 2Zm0 0v15m-4.5 0h9");
}

</style>
