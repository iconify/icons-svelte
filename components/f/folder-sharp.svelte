<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u56kdfmjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-sharp" {...props}></Icon>
<style>
:global(.u56kdfmjm) {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14z");
}

</style>
