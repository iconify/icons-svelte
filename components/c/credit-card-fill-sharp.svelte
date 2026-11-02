<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd7anpj2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-fill-sharp" {...props}></Icon>
<style>
:global(.dd7anpj2o) {
  fill: currentColor;
  d: path("M22 8H2V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Zm0 2v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9Zm-11 4H7a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2");
}

</style>
