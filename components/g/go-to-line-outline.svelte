<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkz96bi0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:go-to-line-outline" {...props}></Icon>
<style>
:global(.fkz96bi0u) {
  fill: currentColor;
  d: path("M11 7V5h2v2zm0 12v-2h2v2z");
}

</style>
