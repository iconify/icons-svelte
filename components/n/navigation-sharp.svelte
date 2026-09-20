<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv-ceeele"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:navigation-sharp" {...props}></Icon>
<style>
:global(.rv-ceeele) {
  fill: currentColor;
  d: path("m5 21l-1-1l8-18l8 18l-1 1l-7-3z");
}

</style>
