<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzdozth7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-add" {...props}></Icon>
<style>
:global(.dzdozth7e) {
  fill: currentColor;
  d: path("M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6z");
}

</style>
