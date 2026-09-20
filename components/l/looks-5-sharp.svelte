<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l02w15boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:looks-5-sharp" {...props}></Icon>
<style>
:global(.l02w15boz) {
  fill: currentColor;
  d: path("M9 17h6v-6h-4V9h4V7H9v6h4v2H9zm-6 4V3h18v18z");
}

</style>
