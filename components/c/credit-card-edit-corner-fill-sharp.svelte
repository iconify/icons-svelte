<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikw6mqbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-edit-corner-fill-sharp" {...props}></Icon>
<style>
:global(.ikw6mqbuo) {
  fill: currentColor;
  d: path("M22 8H2V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Zm-12 2v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9Zm2 11v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

</style>
