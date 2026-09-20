<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzm3qb5pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:exposure-neg-1-outline" {...props}></Icon>
<style>
:global(.fzm3qb5pc) {
  fill: currentColor;
  d: path("M10 14H3v-2h7zm5.75 5V8.05l-2.3 1.65l-1.15-1.75L16.4 5H18v14z");
}

</style>
