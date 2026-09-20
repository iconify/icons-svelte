<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wocj8g3zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:looks-two-sharp" {...props}></Icon>
<style>
:global(.wocj8g3zg) {
  fill: currentColor;
  d: path("M9 17h6v-2h-4v-2h4V7H9v2h4v2H9zm-6 4V3h18v18z");
}

</style>
