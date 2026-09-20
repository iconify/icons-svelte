<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mehmunbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-arrow-up-right-outline-sharp" {...props}></Icon>
<style>
:global(.mehmunbaa) {
  fill: currentColor;
  d: path("m9.9 15.5l3.1-3.1V15h2V9H9v2h2.6l-3.1 3.1zM5 23V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>
