<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smfebfddh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-end-diamond-sharp" {...props}></Icon>
<style>
:global(.smfebfddh) {
  fill: currentColor;
  d: path("m15 16.77l-4.27-4.27H3.078v-1h7.654L15 7.23L19.77 12z");
}

</style>
