<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oprhzeb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:fast-rewind-outline-sharp" {...props}></Icon>
<style>
:global(.oprhzeb7h) {
  fill: currentColor;
  d: path("M19.904 16.616L12.98 12l6.923-4.615zm-8.885 0L4.096 12l6.923-4.615zm-1-1.866v-5.5L5.89 12zm8.885 0v-5.5L14.773 12z");
}

</style>
