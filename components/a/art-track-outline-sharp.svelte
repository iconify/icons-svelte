<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgk_pbbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:art-track-outline-sharp" {...props}></Icon>
<style>
:global(.xgk_pbbay) {
  fill: currentColor;
  d: path("M13.77 18h-12V6h12zm-11-1h10V7h-10zM17 18V6h1v12zm4.23 0V6h1v12zm-17-3.23h7.078l-2.139-2.886l-1.9 2.5l-1.4-1.85zM2.77 7v10z");
}

</style>
