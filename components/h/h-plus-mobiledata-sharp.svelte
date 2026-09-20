<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-kve-brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:h-plus-mobiledata-sharp" {...props}></Icon>
<style>
:global(.u-kve-brd) {
  fill: currentColor;
  d: path("M4.616 17V7h1v4.5h7V7h1v10h-1v-4.5h-7V17zm13.769-2.5v-2h-2v-1h2v-2h1v2h2v1h-2v2z");
}

</style>
