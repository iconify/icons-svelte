<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg5ib972w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:azm-sharp" {...props}></Icon>
<style>
:global(.dg5ib972w) {
  fill: currentColor;
  d: path("m15.904 15.5l2.904-2.904V5h-7.596L8.308 7.904h7.596zM11 20.404l2.904-2.904V9.904H6.308l-2.904 2.904H11z");
}

</style>
