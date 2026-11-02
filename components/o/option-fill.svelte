<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzlj2ol0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:option-fill" {...props}></Icon>
<style>
:global(.uzlj2ol0i) {
  fill: currentColor;
  d: path("M3 6h6c.351 0 .677.184.857.486L15.566 16H21a1 1 0 0 1 0 2h-6a1 1 0 0 1-.857-.486L8.434 8H3a1 1 0 0 1 0-2m12 0h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>
