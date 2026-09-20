<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm19ufxjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-9-16-sharp" {...props}></Icon>
<style>
:global(.zm19ufxjq) {
  fill: currentColor;
  d: path("M7 21V3h10v18z");
}

</style>
