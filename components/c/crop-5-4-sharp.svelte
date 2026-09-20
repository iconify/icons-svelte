<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0nalbcir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-5-4-sharp" {...props}></Icon>
<style>
:global(.v0nalbcir) {
  fill: currentColor;
  d: path("M4 19V5h16v14z");
}

</style>
