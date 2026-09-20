<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz9g9ubfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flag-2-outline-sharp" {...props}></Icon>
<style>
:global(.nz9g9ubfk) {
  fill: currentColor;
  d: path("M5 22V3h16l-2 5l2 5H7v9zm2-11h11.05l-1.2-3l1.2-3H7zm0 0V5z");
}

</style>
