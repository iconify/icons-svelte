<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjovd25sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:credit-card-outline-sharp" {...props}></Icon>
<style>
:global(.vjovd25sv) {
  fill: currentColor;
  d: path("M2 20V4h20v16zM4 8h16V6H4zm0 10h16v-6H4zm0 0V6z");
}

</style>
