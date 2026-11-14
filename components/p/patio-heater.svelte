<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5o4owd1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:patio-heater" {...props}></Icon>
<style>
:global(.o5o4owd1o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 7l3-3.5h6L18 7Zm6 0v13.5m-3.5 0h7M8 10q-1 1.5 0 3t0 3m8-6q-1 1.5 0 3t0 3");
}

</style>
