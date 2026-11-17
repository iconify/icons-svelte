<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlhtppbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-code-fill-round" {...props}></Icon>
<style>
:global(.jlhtppbji) {
  fill: currentColor;
  d: path("M8 3h8a5 5 0 0 1 5 5v5a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5m2.707 6.207a.999.999 0 1 0-1.414-1.414l-2 2a.997.997 0 0 0 0 1.414l2 2a.999.999 0 1 0 1.414-1.414L9.414 10.5Zm6 .586l-2-2a.999.999 0 1 0-1.414 1.414l1.293 1.293l-1.293 1.293a.999.999 0 1 0 1.414 1.414l2-2a1 1 0 0 0 0-1.414M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
