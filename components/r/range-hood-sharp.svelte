<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6frw66jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:range-hood-sharp" {...props}></Icon>
<style>
:global(.o6frw66jc) {
  fill: currentColor;
  d: path("M3.05 12L7 8V3h10v5l4 4zM2 20v-6h20v6zm8-3.3h4v-1.5h-4z");
}

</style>
