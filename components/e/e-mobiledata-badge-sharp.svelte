<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftq1pmo9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:e-mobiledata-badge-sharp" {...props}></Icon>
<style>
:global(.ftq1pmo9p) {
  fill: currentColor;
  d: path("M8 17h8v-2h-6v-2h5v-2h-5V9h6V7H8zm-5 4V3h18v18z");
}

</style>
