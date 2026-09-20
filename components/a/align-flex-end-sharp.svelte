<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-9s9sbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-flex-end-sharp" {...props}></Icon>
<style>
:global(.t-9s9sbjt) {
  fill: currentColor;
  d: path("M3 21v-1h18v1zm8-4V4h2v13z");
}

</style>
