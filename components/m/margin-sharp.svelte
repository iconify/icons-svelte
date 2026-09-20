<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibtz_jbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:margin-sharp" {...props}></Icon>
<style>
:global(.ibtz_jbig) {
  fill: currentColor;
  d: path("M3 21V3h18v18zM7 9h2V7H7zm4 0h2V7h-2zm4 0h2V7h-2zm-8 4h2v-2H7zm4 0h2v-2h-2zm4 0h2v-2h-2z");
}

</style>
