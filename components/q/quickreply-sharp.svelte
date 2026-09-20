<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o43y7qbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:quickreply-sharp" {...props}></Icon>
<style>
:global(.o43y7qbvi) {
  fill: currentColor;
  d: path("M18.923 20.77V17h-1.23v-4.615h2.788l-1.123 3.23h1.757zM3 20.076V3h18v6.616h-6.077V17H6.077z");
}

</style>
