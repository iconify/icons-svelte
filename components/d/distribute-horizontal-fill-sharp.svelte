<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_-11ub5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-horizontal-fill-sharp" {...props}></Icon>
<style>
:global(.y_-11ub5h) {
  fill: currentColor;
  d: path("M5 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm16 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM8 18V6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

</style>
