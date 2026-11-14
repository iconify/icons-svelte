<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr1mwnbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:list-collapse" {...props}></Icon>
<style>
:global(.vr1mwnbut) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6h8.5M12 12h8.5M12 18h8.5M3.5 4L6 6.5L8.5 4m-5 16L6 17.5L8.5 20");
}

</style>
