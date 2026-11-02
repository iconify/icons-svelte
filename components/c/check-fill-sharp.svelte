<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi26zpr3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-fill-sharp" {...props}></Icon>
<style>
:global(.vi26zpr3v) {
  fill: currentColor;
  d: path("m10 14.586l7.293-7.293a.999.999 0 1 1 1.414 1.414l-8 8a1 1 0 0 1-1.414 0l-4-4a.999.999 0 1 1 1.414-1.414Z");
}

</style>
