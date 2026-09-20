<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar-oh8bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:markunread-mailbox-sharp" {...props}></Icon>
<style>
:global(.ar-oh8bhs) {
  fill: currentColor;
  d: path("M3 21V9h3.616V3h6.5v3.616h-5.5V14H10V9h11v12z");
}

</style>
