<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4defabxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lab-balance" {...props}></Icon>
<style>
:global(.w4defabxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v16.5m-4 0h8M6 7h12M6 7l-3 6.5a3 3 0 0 0 6 0L6 7m12 0l-3 6.5a3 3 0 0 0 6 0L18 7");
}

</style>
