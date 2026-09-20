<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abe6--brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crossword" {...props}></Icon>
<style>
:global(.abe6--brr) {
  fill: currentColor;
  d: path("M9 22v-6h6v6zm-7-7V9h6v6zm7 0V9h6v6zm7 0V9h6v6zm0-7V2h6v6z");
}

</style>
