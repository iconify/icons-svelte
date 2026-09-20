<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm8-g6wmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:next-week-outline-sharp" {...props}></Icon>
<style>
:global(.tm8-g6wmf) {
  fill: currentColor;
  d: path("M3 20V7h6V4h6v3h6v13zm1-1h16V8H4zm6-12h4V5h-4zM4 19V8zm7-2.192l3.308-3.308L11 10.192l-.708.708l2.6 2.6l-2.6 2.6z");
}

</style>
