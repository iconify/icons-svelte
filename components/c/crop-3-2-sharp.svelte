<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq8syh52f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-3-2-sharp" {...props}></Icon>
<style>
:global(.dq8syh52f) {
  fill: currentColor;
  d: path("M4 17V7h16v10z");
}

</style>
