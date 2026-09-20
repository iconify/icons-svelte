<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n24o--baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:files-sharp" {...props}></Icon>
<style>
:global(.n24o--baw) {
  fill: currentColor;
  d: path("M2 20v-5h11V4h9v16zm0-6V6h8zm3.825-1L11 7.825V13z");
}

</style>
