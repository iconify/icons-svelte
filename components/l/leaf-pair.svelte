<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy--grbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:leaf-pair" {...props}></Icon>
<style>
:global(.dy--grbge) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11c0-4.5-3-7-8.5-7c0 4.5 3 7 8.5 7Zm0 0c0-4.5 3-7 8.5-7c0 4.5-3 7-8.5 7Zm0 0v10");
}

</style>
