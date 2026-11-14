<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu9w0l01r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:discount-tiered" {...props}></Icon>
<style>
:global(.zu9w0l01r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5v-3h6v-3h6v-3h7v9ZM16.677 3.788l4.596 4.596l-3.889 3.889l-4.596-4.596V3.788ZM15.97 6.97h.01");
}

</style>
