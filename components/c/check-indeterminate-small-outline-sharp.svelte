<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-aohbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:check-indeterminate-small-outline-sharp" {...props}></Icon>
<style>
:global(.fq-aohbnb) {
  fill: currentColor;
  d: path("M7 12.5v-1h10v1z");
}

</style>
