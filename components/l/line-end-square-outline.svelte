<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oldmkuwnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-end-square-outline" {...props}></Icon>
<style>
:global(.oldmkuwnp) {
  fill: currentColor;
  d: path("M13 15.5h7v-7h-7zm-2 2V13H2v-2h9V6.5h11v11zm5.5-5.5");
}

</style>
