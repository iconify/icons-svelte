<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtffjhhpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:floor-lamp-sharp" {...props}></Icon>
<style>
:global(.mtffjhhpv) {
  fill: currentColor;
  d: path("M11.52 19v-8H6.015l2.178-7h7.65l2.179 7h-5.504v8zm-3 2v-1h7v1z");
}

</style>
