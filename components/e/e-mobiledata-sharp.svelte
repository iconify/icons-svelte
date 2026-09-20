<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo8v-yb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:e-mobiledata-sharp" {...props}></Icon>
<style>
:global(.qo8v-yb4b) {
  fill: currentColor;
  d: path("M8 17V7h8v2h-6v2h6v2h-6v2h6v2z");
}

</style>
