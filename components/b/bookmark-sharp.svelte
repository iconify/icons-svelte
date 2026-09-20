<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uazgjac8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bookmark-sharp" {...props}></Icon>
<style>
:global(.uazgjac8v) {
  fill: currentColor;
  d: path("M5 21V3h14v18l-7-3z");
}

</style>
