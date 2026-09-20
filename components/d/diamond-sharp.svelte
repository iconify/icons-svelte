<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ammjlfgop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:diamond-sharp" {...props}></Icon>
<style>
:global(.ammjlfgop) {
  fill: currentColor;
  d: path("M9.027 8.558L11.562 3.5h.877l2.534 5.058zm2.53 11.119L3.03 9.442h8.529zm.885 0V9.442h8.53zm3.508-11.12L13.427 3.5h5.265l2.53 5.058zm-13.171 0L5.308 3.5h5.265L8.05 8.558z");
}

</style>
