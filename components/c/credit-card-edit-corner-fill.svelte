<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdt0eso7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-edit-corner-fill" {...props}></Icon>
<style>
:global(.jdt0eso7u) {
  fill: currentColor;
  d: path("M22 8H2V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3Zm-12 2v9a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-7Zm2 11v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

</style>
