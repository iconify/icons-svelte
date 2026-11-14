<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf7yo1bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:baguette" {...props}></Icon>
<style>
:global(.wf7yo1bgn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.338 16.773L16.773 3.338l3.889 3.889L7.227 20.662Zm2.828-2.828l5.304 2.474m-2.122-5.656l5.304 2.474M12.53 7.581l5.304 2.474");
}

</style>
