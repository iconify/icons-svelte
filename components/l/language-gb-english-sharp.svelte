<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgpspid6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:language-gb-english-sharp" {...props}></Icon>
<style>
:global(.hgpspid6g) {
  fill: currentColor;
  d: path("M15 15h4v-2h-4zm0-4h4V9h-4zM3 17V7h8v2H5v6h4v-2H7v-2h4v6zm10 0V7h7l1 1v3l-1 1l1 1v3l-1 1z");
}

</style>
