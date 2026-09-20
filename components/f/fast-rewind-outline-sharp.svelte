<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggg3fccdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fast-rewind-outline-sharp" {...props}></Icon>
<style>
:global(.ggg3fccdt) {
  fill: currentColor;
  d: path("m21.5 18l-9-6l9-6zm-10 0l-9-6l9-6zm-2-3.75v-4.5L6.1 12zm10 0v-4.5L16.1 12z");
}

</style>
