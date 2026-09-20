<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa2x56nbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:currency-yuan" {...props}></Icon>
<style>
:global(.sa2x56nbq) {
  fill: currentColor;
  d: path("M11 21v-7H6v-2h4.725L5 3h2.375L12 10.3L16.625 3H19l-5.725 9H18v2h-5v7z");
}

</style>
