<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbax_44cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:experiment-start" {...props}></Icon>
<style>
:global(.sbax_44cj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.216 21H2.5l6-12V2.5H13V9l.805 1.61M6.5 13h5.7m2.8 1.5l6 3.5l-6 3.5Z");
}

</style>
