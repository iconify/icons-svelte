<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-nw7fb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:ink-marker-outline-sharp" {...props}></Icon>
<style>
:global(.t-nw7fb5g) {
  fill: currentColor;
  d: path("m6.839 20.016l-.835-.835L4.6 20.585l-1.135-1.158l1.393-1.392l-.835-.846l13.21-13.21l2.826 2.827zm4.261-8.477l-5.661 5.65L6.85 18.6l5.65-5.661z");
}

</style>
